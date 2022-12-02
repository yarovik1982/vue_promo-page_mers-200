<template>
   <section class="section design" id="design">
		<div class="container">
			<div class="design-wrapper">
				<div class="design-block">
					<img src="@/assets/img/car/image-5.png" alt="A 200" class="feature__img design-block__img"
						data-tabs-field="interior">
            
					<img src="@/assets/img/car/image-4.png" alt="A 200" class="feature__img design-block__img hidden"
						data-tabs-field="body">
					<div class="design-text">
						<h2 class="section__title design__title">
							Комфорт в деталях
						</h2>
						<h2 class="section__title design__title hidden">
							Притягивает взгляды
						</h2>
						<ul class="design-list">
							<li>
								<button type="button" class="design-list__item design-list__item_active"
									data-tabs-handler="interior" data-some-attr="attr">Дизайн салона</button>
							</li>
							<li>
								<button type="button" class="design-list__item" data-tabs-handler="body">Дизайн
									кузова</button>
							</li>
						</ul>
						<!-- /.design-list -->
						<ul>
							<li class="design__descr" data-tabs-field="interior">
								<p class="design__description-text">
									Будь то час пик, длительная ночная поездка или незнакомая дорога, ваш новый A-Class
									седан ощутимо снимет с вас нагрузку, особенно в стрессовых ситуациях. Время, которое
									вы проводите за рулем автомобиля, не должно проходить впустую. Это время для
									восстановления сил. Автомобиль надежно и с комфортом доставит вас до места
									назначения.
								</p>
								<button class="more">
									— Узнать больше
								</button>
							</li>
							<li class="design__descr hidden" data-tabs-field="body">
								<p class="design__description-text">
									Благодаря длинной задней части, новый A-Class Sedan обладает еще лучшими
									аэродинамическими показателями, чем A-Class Hatchback (Cd от 0,25). С показателем
									0,22 новая модель седана сравнялась с мировым рекордом CLA Coupe. A-Class Sedan
									имеет самое низкое аэродинамическое сопротивление среди всех серийных автомобилей в
									мире.
								</p>
								<button class="more">
									— Узнать больше
								</button>
							</li>
						</ul>
					</div>
			
				</div>
          <ul>
					<li class="design-images" data-tabs-field="interior">
            
						<img src="@/assets/img/design/interior01.jpg" alt="A 200" class="design__img">
						<img src="@/assets/img/design/interior02.jpg " alt="A 200" class="design__img">
						<img src="@/assets/img/design/interior03.jpg " alt="A 200" class="design__img">
						<img src="@/assets/img/design/interior04.jpg" alt="A 200" class="design__img">
					</li>
					<li class="design-images hidden" data-tabs-field="body">
						<img src="@/assets/img/design/body01.jpg" alt="A 200" class="design__img">
						<img src="@/assets/img/design/body02.jpg" alt="A 200" class="design__img">
						<img src="@/assets/img/design/body03.jpg" alt="A 200" class="design__img">
						<img src="@/assets/img/design/body04.jpg" alt="A 200" class="design__img">
					</li>
				</ul>
				
			</div>
			
		</div>
	</section>
</template>