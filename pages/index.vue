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
              Стоимость: <span style="text-decoration: line-through; font-weight: 100;">5000 тенге</span> <br>
              <span style="margin-top:10px;">3000 тенге</span>
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
      <div style="display: flex; justify-content: flex-end;">
        <div style="width: 50.5rem;" >
          <p style="text-align: right;">
            <span style="font-weight: 400; font-size: 20px">
            <i>«Если бы такие проекты начались намного раньше, женщины всего мира получили бы возможность стать свободнее, полноценнее, и счастливее..» </i>
            </span>
            <br>
            <br>
            <span style="font-weight: 600; font-size: 20px; text-align: right; margin-top: 10px;"> Айым Алтынбекова </span>
          </p>
        </div>
      </div>
      <div style="margin-top: 40px;">
      
        <p>
         Я Айым Алтынбекова, и я приглашаю вас на свой интенсив! Вся программа интесива направлена на одну, но самую главную цель – получение сакральных знаний, которые изменят вашу реальность. Это настоящий тест- драйв в новое измерение. Я подготовила мощную программу, и включила в нее знания многих успешных и профессиональных людей. Тех людей, которым ты бы хотела задать вопросы, но так долго не решалась. Миссия интенсива - привести тебя к состоянию , в котором ты уверена в себе, счастлива , легка на подъём , именно из этого состояния складывается картинка того, чего ты действительно хочешь в жизни. И это еще не все. Интересно? Значит, трансформация уже началась. Мы ждем тебя!
        </p>
      </div>
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
               Альмира Турсын
              </div>

              <div class="card__subtitle">
                Актриса, сценарист и женский коуч-профориентатор
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__text">
                  «Как найти своё призвание», «Как создать любимое дело», профориентация.
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/almiratursyn/" target="_blank" class="card__text card__text--flex">
                  <span>@almiratursyn</span>
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
               Айнур Кубек 
              </div>

              <div class="card__subtitle">
                Парфюмер, аромапсихолог
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Тема:
                </div>
                <div class="card__themes">
                  <div class="card__text">
                    Аромапсихология: влияние ароматов на психо-эмоциональное состояние. «Ваши предпочтения в ароматах могут многое о вас рассказать..»
                  </div>
                </div>
              </div>

              <div class="card__section">
                <div class="card__bold">
                  Inst:
                </div>
                <a href="https://www.instagram.com/ainur.qubek/" target="_blank" class="card__text card__text--flex">
                  <span>@ainur.qubek </span>
                  <svg width="24" height="24">
                    <use href="../assets/img/icons.svg#share"></use>
                  </svg>
                </a>
              </div>
            </div>
          </div>

          <div class="speaker-section__card card card--3">
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
                    Финансы 2022 года, что нас ждёт?
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
                    Любовь и привязанность
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
                      Обмен энергией между мужчиной и женщиной
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
                    Как воспитать уверенного в себе ребёнка?
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
                   Про воспитание, ПОКА ЧТО ТАК, будем менять
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
