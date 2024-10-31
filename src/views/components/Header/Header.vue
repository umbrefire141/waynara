<template>
	<header class="header">
		<div class="container">
			<div class="logo">
				<img src="@/assets/images/logo.png" />
			</div>
			<nav class="menu">
				<ul class="list">
					<li class="item active">
						<RouterLink to="/" class="link">
							Главная
						</RouterLink>
					</li>
					<li class="item">
						<RouterLink to="/" class="link">
							О проекте
						</RouterLink>
					</li>
					<li class="item">
						<RouterLink to="/" class="link">
							Войти
						</RouterLink>
					</li>
					<li class="item">
						<RouterLink to="/" class="link">
							Регистрация
						</RouterLink>
					</li>
				</ul>
			</nav>
		</div>
	</header>
</template>
<script lang="ts">
import { defineComponent } from "vue"
export default defineComponent({

})
</script>
<style scoped>
.header {
	right: 0;
	left: 0;
	position: absolute;
	color: #fff;
	padding-top: 24px;
}

.container {
	display: flex;
	justify-content: space-between;
	align-items: center;
	width: 100%;
}

.list {
	display: flex;
	align-items: center;
	gap: 12px;
}

.item {
	position: relative;
	z-index: 1;
	font-size: 1.125rem;
	padding: 0 32px;
}

.active {
	padding: 0.01rem 1rem;
	font-weight: 600;
	color: var(--color-purple);
}

.active::before {
	content: '';
	background-color: #fff;
	position: absolute;
	clip-path: polygon(0 0, 89% 0, 98% 100%, 2% 100%);
	right: 0;
	top: 0;
	bottom: 0;
	left: 0;
	z-index: -1;
}
</style>