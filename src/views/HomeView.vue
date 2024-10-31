<template>
	<Header />
	<main class="main">
		<div class="choice">
			<div class="container">
				<!-- Make component typography -->
				<div>Выбери свой активный отдых</div>
				<div>
					<div>
						<label>Вид активности</label>
						<!-- Dropdown -->
					</div>
					<div>
						<label>Место</label>
						<!-- Dropdown -->
					</div>
					<!-- Button -->
				</div>
			</div>
		</div>
		<div class="about">
			<!-- Typography -->
			<div>О нас</div>
			<div>
				<img src="../assets/images/logo-blue.svg" />
				<!-- Typography -->
				<div>Wayver – это online сообщество для людей, которые открывают для себя новые направления жизни, расширяют
					границы своих возможностей и практикуют активный и здоровый образ жизни. Wayver поможет получить системную и
					полезную информацию о любом спортивном событии будь то марафон, забег на 10 км, лыжные гонки или иной
					событийный туризм. </div>
			</div>
		</div>
		<div class="events">
			<!-- Typography -->
			<div>Топ событий месяца</div>
			<div>
				<div>
					<img src="../assets/images/events/img-1.jpg" alt="">
					<div>12 июл | СПб</div>
					<div>OCEANMAN</div>
				</div>
			</div>
		</div>
		<div class="blog">
			<!-- Typography -->
			<div>Блог</div>
			<div>Читайте статьи о событиях активного туризма от профессионалов и любителей</div>
			<div>
				<div>
					<img src="../assets/images/events/img-1.jpg" alt="">
					<img src="../assets/images/avatar.jpg" alt="" class="avatar">
					<div>Проф велогонщик</div>
					<div>Андрей Иванов</div>
					<div>Самая сложная трасса года</div>
				</div>
			</div>
		</div>
	</main>
</template>
<script setup lang="ts">
import Header from './components/Header/Header.vue'
</script>
<style scoped>
.choice {
	width: 100vw;
	height: 100vh;
	background-image: url("../assets/images/main-image-bg.jpg");
	background-size: cover;
	background-position: center;
	display: flex;
	justify-content: center;
	align-items: center;
}
</style>