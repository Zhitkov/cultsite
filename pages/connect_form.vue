<template>
  <section class="contact-form">
    <div class="contact-form__content">
      <div class="contact-form__inner">
        <header class="contact-form__header">
          <h1 class="contact-form__title">заказать проект</h1>
          <p class="contact-form__description">
            В нашем портфолио собраны проекты различной направленности:
            <br />от интерактивного приложения исторической библиотеки, до реализации музеев под ключ. К любой задаче мы подходим с особым вниманием, выбирая решения, которые подойдут именно Вам.<br /><br />Для начала работы нам надо поговорить. Достаточно рассказать о своем проекте, указать контакты, и мы свяжемся, чтобы все обсудить.
          </p>
        </header>
        <div class="project-form">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/e07097e6b72cc942b2e0f0e87759997d92cce2d4340008ca2da1eb778d25f7c3?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="" class="project-form__background" />
          <h2 class="project-form__subtitle">Новый проект:</h2>
          <div class="project-form__options">
            <button class="project-form__option project-form__option--active">экспозиционное и выставочное оборудование</button>
            <button class="project-form__option">дизайн проект</button>
          </div>
          <div class="project-form__options">
            <button class="project-form__option">рабочий проект</button>
            <button class="project-form__option">концепция экспозиции</button>
          </div>
          <div class="project-form__options">
            <button class="project-form__option">программное обеспечение</button>
            <button class="project-form__option">виртуальная реальность</button>
          </div>
          <button class="project-form__option">дополненная реальность</button>
          <form class="project-form__fields">
            <div class="form-field">
              <label for="company" class="form-field__label">название компании</label>
              <input type="text" id="company" class="form-field__input" />
            </div>
            <div class="form-field">
              <label for="project-description" class="form-field__label">несколько слов о проекте и приблизительный бюджет</label>
              <textarea id="project-description" class="form-field__input form-field__input--textarea"></textarea>
            </div>
            <div class="form-field">
              <label for="email" class="form-field__label">электронная почта</label>
              <input type="email" id="email" class="form-field__input" />
            </div>
            <div class="form-field">
              <label for="phone" class="form-field__label">телефон или любой удобный мессенджер</label>
              <input type="tel" id="phone" class="form-field__input" value="+7 777 777 77 77" />
            </div>
            <div class="form-field">
              <label for="name" class="form-field__label">имя</label>
              <input type="text" id="name" class="form-field__input" />
            </div>
            <div class="form-field">
              <label for="file-upload" class="form-field__label">приложить файлы <span class="form-field__sublabel">(до 10 мб)</span></label>
              <input type="file" id="file-upload" class="form-field__input form-field__input--file" multiple />
            </div>
            <button type="submit" class="project-form__submit">отправить заявку</button>
          </form>
        </div>
      </div>
      <footer class="contact-form__footer">
        <div class="contact-form__circle"></div>
        <div class="contact-form__bar"></div>
        <button class="contact-form__cta">работать с нами</button>
      </footer>
    </div>
  </section>
</template>

<style scoped>
.contact-form {
  background-color: #fafafa;
  font-family: TT Fors Trial, sans-serif;
  overflow: hidden;
}

.contact-form__content {
  background-color: #475eea;
  display: flex;
  width: 100%;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: space-between;
}

.contact-form__inner {
  background-color: #fafafa;
  display: flex;
  flex-direction: column;
  padding: 54px 0;
}

.contact-form__header {
  z-index: 10;
  display: flex;
  flex-direction: column;
  color: #475eea;
  padding: 0 44px;
}

.contact-form__title {
  font-size: 60px;
  font-weight: 700;
  line-height: 1;
  align-self: start;
}

.contact-form__description {
  font-size: 22px;
  font-weight: 400;
  line-height: 25px;
  margin-top: 57px;
}

.project-form {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 733px;
  margin-top: -75px;
  width: 842px;
  max-width: 100%;
  align-items: start;
  font-size: 22px;
  font-weight: 400;
  line-height: 1;
  padding: 131px 0 13px 44px;
}

.project-form__background {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.project-form__subtitle {
  position: relative;
  color: #5d5d5d;
  font-size: 18px;
  line-height: 1;
}

.project-form__options {
  position: relative;
  align-self: stretch;
  display: flex;
  gap: 15px;
  font-weight: 500;
  text-align: center;
  flex-wrap: wrap;
  margin: 36px -28px 0 0;
}

.project-form__option {
  border-radius: 200px;
  color: #475eea;
  padding: 23px 37px;
  border: 2px solid #475eea;
  background: none;
  font-size: inherit;
  cursor: pointer;
}

.project-form__option--active {
  background-color: #475eea;
  color: #fff;
}

.form-field {
  margin-top: 35px;
}

.form-field__label {
  color: #5d5d5d;
  display: block;
  margin-bottom: 10px;
}

.form-field__input {
  width: 100%;
  border: none;
  border-bottom: 1px solid #a1a1a1;
  padding: 10px 0;
  font-size: 22px;
  background: transparent;
}

.form-field__input--textarea {
  height: 100px;
  resize: vertical;
}

.form-field__input--file {
  border: none;
}

.project-form__submit {
  border-radius: 75px;
  background-color: #475eea;
  box-shadow: 6px 6px 8px rgba(0, 0, 0, 0.15);
  align-self: center;
  margin-top: 64px;
  width: 360px;
  max-width: 100%;
  font-size: 27px;
  color: #fff;
  font-weight: 700;
  text-align: center;
  line-height: 1;
  padding: 30px 57px;
  border: none;
  cursor: pointer;
}

.contact-form__footer {
  align-self: start;
  display: flex;
  margin-top: 55px;
  flex-direction: column;
  font-size: 27px;
  color: #fff;
  font-weight: 700;
  text-align: center;
  line-height: 1;
}

.contact-form__circle {
  border-radius: 50%;
  width: 202px;
  height: 202px;
  border: 2px solid #475eea;
}

.contact-form__bar {
  border-radius: 50px;
  background-color: #000;
  margin-top: 423px;
  height: 64px;
}

.contact-form__cta {
  border-radius: 75px;
  background-color: #475eea;
  box-shadow: 6px 6px 8px rgba(0, 0, 0, 0.15);
  align-self: end;
  margin-top: 124px;
  width: 403px;
  max-width: 100%;
  padding: 27px 70px;
  border: none;
  color: #fff;
  font-size: inherit;
  font-weight: inherit;
  cursor: pointer;
}

@media (max-width: 991px) {
  .contact-form__content,
  .contact-form__inner,
  .contact-form__header,
  .contact-form__title,
  .contact-form__description,
  .project-form,
  .project-form__submit,
  .contact-form__footer,
  .contact-form__bar,
  .contact-form__cta {
    max-width: 100%;
  }

  .contact-form__header {
    padding: 0 20px;
  }

  .contact-form__title {
    font-size: 40px;
  }

  .contact-form__description,
  .project-form,
  .project-form__submit,
  .contact-form__footer,
  .contact-form__bar,
  .contact-form__cta {
    margin-top: 40px;
  }

  .project-form {
    padding: 100px 0 0 20px;
  }

  .project-form__option,
  .project-form__submit,
  .contact-form__cta {
    padding: 0 20px;
  }
}
</style>