
<template>
  <p class="text-h1">Inica el camino del curso con los siguientes temas: </p>
	<div ref="content"></div>
	<button>Continuar</button>


</template>
<script setup>
import { ref } from 'vue'
// Data
const data = [
	{
		n: "Brain Training",
		s:
			"https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/brain-training.svg"
	},
	{
		n: "Culture",
		s:
			"https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/culture.svg"
	},
	{
		n: "Family & Friends",
		s:
			"https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/family-and-friends.svg"
	},
	{
		n: "Job Opportunities",
		s:
			"https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/job-opportunities.svg"
	},
	{
		n: "School",
		s:
			"https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/school.svg"
	},
	{
		n: "Travel",
		s:
			"https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/travel.svg"
	},
	{
		n: "Just For Fun",
		//s: "https://d35aaqx5ub95lt.cloudfront.net/images/owls/spread.svg"
        s: "https://pixabay.com/es/vectors/base-de-datos-icono-m%C3%B3vil-2389207/"
	},
	{
		n: "Other",
		s:
			"https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/other.svg"
	}
];

// DOM ref handles
const content = ref("content");

// Generate cards
data.forEach((d) => {
	// HTML card template
	let html = `
		<div class="card">
			<img src="${d.s}">
			<p>${d.n}</p>
		</div>
	`;
	// Push card template to content div
	content.innerHTML += html;
});


</script>
<style scoped>


* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: "Avenir", sans-serif;
}

body {
	display: flex;
	height: 100vh;
	width: 100%;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

main {
	height: 100%;
	width: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
}

h2 {
	text-align: center;
}

.content {
	height: 400px;
	width: 800px;
	margin-top: 32px;
	display: grid;
	place-self: center;
	grid-auto-rows: 1fr;
	grid-gap: 8px;
	grid-template-columns: repeat(4, 1fr);
}

.content .card {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	padding: 16px 24px;
	height: 176px;
	width: 188px;
	border: solid #e5e5e5;
	border-width: 2px 2px 4px;
	border-radius: 16px;
	cursor: pointer;
	transition: all 0.3s;
}

.content .card:hover {
	background: #f0f0f0;
	border-width: 2px;
}

.content .card img {
	height: 80px;
	margin-bottom: 12px;
}

.content .card p {
	font-size: 14px;
}

button {
	display: flex;
	justify-content: center;
	align-items: center;
	letter-spacing: 1px;
	height: 48px;
	width: 800px;
	border: none;
	outline: none;
	border-radius: 16px;
	background: #58cc02;
	margin-top: 16px;
	border: solid #58a700;
	border-width: 0px 0px 4px;
	font-size: 14px;
	text-transform: uppercase;
	color: #fff;
	font-weight: 600;
	cursor: pointer;
}

</style>