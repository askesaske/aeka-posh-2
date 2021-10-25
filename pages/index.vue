<template>
  <main class="main">

    <section class="main__section welcome-section">
      <div class="welcome-section__container">

        <a href="https://api.whatsapp.com/message/QGQGYLGDBLRVC1" target="_blank" class="button-wpp welcome-section__wpp-btn">
          <svg width="20" height="20">
            <use href="../assets/img/icons.svg#wpp"></use>
          </svg>
          <p>+7 776 502 3636</p>
        </a>

        <div class="welcome-section__main">
          <div class="welcome-section__info">
            <h1 class="welcome-section__title">
              Интенсив для <br>
              женщин и девушек
            </h1>

            <p class="welcome-section__subtitle">
              Стоимость: <span>5000 тенге</span>
            </p>

            <div class="welcome-section__btn" v-scroll-to="{el:'#speakers', duration: 1500,}">
              <button class="button">
                Узнать подробнее
              </button>
              <svg width="12" height="105" class="welcome-section__arrow welcome-section__arrow--desktop">
                <use href="../assets/img/icons.svg#arrow-sm"></use>
              </svg>
              <svg width="12" height="58" class="welcome-section__arrow welcome-section__arrow--phone">
                <use href="../assets/img/icons.svg#arrow-sm"></use>
              </svg>
            </div>
          </div>

          <img src="../assets/img/welcome-img.png" alt="" class="welcome-section__img">
        </div>

      </div>
    </section>

    <section class="main__section about-section">
      <div class="about-section__container">
        <p>
          Я, <span>Айым Алтынбекова</span>, приглашаю Вас на мой интенсив, рассчитаный на тех женщин, 
          которые хотят жить полноценной жизнью, для тех, кто хочет проявлять себя во всех жизненных аспектах. 
          Родовые задачи, психологию, предназначение, отношения, питание, женские практики, и многое другое вам 
          будут преподавать спикеры знающие своё направление на отлично. За <span>10 дней</span> вы получите не просто 
          полноценные знания, но и научитесь применять их в своей жизни,  <span>меняя свою реальность.</span> 
          Приглашаю начать новую жизнь, где вы всегда счастливы, любимы, имеете достаточно денег и самое 
          главное находитесь в гармонии с самой собой. 
          <br>
          Вы почувствуете приток новых сил, приобретёте внутреннее равновесие, и баланс. Создайте свою счастливую реальность вместе с нами.
        </p>
      </div>
    </section>

    <section class="main__section speaker-section" id="speakers">
      <div class="speaker-section__container">
        <h2 class="speaker-section__title">
          Наши спикеры
        </h2>

        <div class="speaker-section__card-list">

          <div class="speaker-section__card card card--1">
            <img src="../assets/img/photo-1.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
                Динара Рафаель 
              </div>

              <div class="card__subtitle">
                Международный нумеролог обучившийся в Оксфорде
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__text">
                  Как прокачать себя с помощью чисел : финансы, карьера, отношение.
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/dinara.raphael/" target="_blank" class="card__text card__text--flex">
                  <span>@dinara.raphael</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--2">
            <img src="../assets/img/photo-2.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
                Галиева Динара Бауыржановна
              </div>

              <div class="card__subtitle">
                Врач-педиатр, нутрициолог, натуропрактик, сертифицированный health коуч по интегративному питанию, магистр медицины, PhD
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__themes">
                  <div class="card__text">
                    Энергия и Питание. Как избавиться от хронической усталости с помощью питания
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/dinara_galiyeva/" target="_blank" class="card__text card__text--flex">
                  <span>@dinara_galiyeva</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--3">
            <img src="../assets/img/photo-3.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
                Санди Султан 
              </div>

              <div class="card__subtitle">
                Телерадиоведущая, журналист с 20-летним опытом работы на ТВ и радио.
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__themes">
                  <div class="card__text">
                    Женская энергия. Как произвести впечатление и говорить так, чтобы Вас услышали.
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/sandi_sultan/" target="_blank" class="card__text card__text--flex">
                  <span>@sandi_sultan</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--4">
            <img src="../assets/img/photo-4.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
                Акрам
              </div>

              <div class="card__subtitle">
                Астролог года 2019 по версии глянцевого журнала People and Teens. Является духовным наставником для
                многих сотен людей
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__themes">
                  <div class="card__text">
                    Медитация успеха. Йога достижения цели
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/akram_astrolog/" target="_blank" class="card__text card__text--flex">
                  <span>@akram_astrolog</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--5">
            <img src="../assets/img/photo-5.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
                Кунекей Нурлан 
              </div>

              <div class="card__subtitle">
                Финансист-практик с общим скажем 13 лет. 
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__themes">
                  <div class="card__text">
                    Финансовая грамотность 
                  </div>
                   <div class="card__text">
                    Финансы фрилансера
                  </div>
                   <div class="card__text">
                    Кредиты. За и против
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/kunekei_finance/" target="_blank" class="card__text card__text--flex">
                  <span>@kunekei_finance</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--4">
            <img src="../assets/img/photo-6.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
               Акгуль Абдали 
              </div>

              <div class="card__subtitle">
                Психолог – психотерапевт. Магистр психологии. Семейный психолог. Является членом Американской Психологической Ассоциации (APA).
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__themes">
                  <div class="card__text">
                    Отношения. Кризисы и как их преодолеть
                  </div>
                  <div class="card__text">
                    Психосоматика наших болезней
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/akgul.abdali/" target="_blank" class="card__text card__text--flex">
                  <span>@akgul.abdali</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--5">
            <img src="../assets/img/photo-7.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
                Нургуль Шаудан
              </div>

              <div class="card__subtitle">
                Практикующий чакролог
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__themes">
                  <div class="card__text">        
                      Родовые и кармические задачи
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/nurgul.shaudan/" target="_blank" class="card__text card__text--flex">
                  <span>@nurgul.shaudan</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--4">
            <img src="../assets/img/photo-8.png" alt="" class="card__img">

            <div class="card__info">
              <div class="card__title">
                Зарина Шегенова 
              </div>

              <div class="card__subtitle">
                Психолог, Автор Трансформационной игры «Поток Жизни», Практик НЛП
              </div>

              <div class="card__section">
                <div class="card__bold card__bold--no-width">
                  Темы:
                </div>
                <div class="card__themes">
                  <div class="card__text">
                    Предназначение. Путь к себе
                  </div>
                   <div class="card__text">
                    Выход из невроза и тревожности. Жизнь с чистого листа
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/aida_psychologist_kz/" target="_blank" class="card__text card__text--flex">
                  <span>@aida_psychologist_kz</span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

        </div>

      </div>
    </section>

    <section class="main__section register-section" id="register">
      <div class="register-section__container">

        <div class="register-section__main">
          <div class="register-section__info">
            <div class="register-section__title">
              Регистрация в WhatsApp
            </div>
            <div class="register-section__subtitle">
              Напиши нам и наши менеджеры все расскажут
            </div>
            <a href="https://api.whatsapp.com/message/QGQGYLGDBLRVC1" target="_blank" class="register-section__btn button">
              Зарегистрироваться
            </a>
          </div>
          <img src="../assets/img/phone-1.png" alt="" class="register-section__img">
        </div>

      </div>
    </section>

  </main>
</template>

<script>
export default {}
</script>

<style>

</style>
