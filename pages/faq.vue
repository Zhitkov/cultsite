<template>
  <div class="faq-page">
    <header class="header">
      <div class="logo-container">
        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/c563e72146e440afafb782343a7d254e0f0e80635e5c4e3e5e5f7d5d9a6e9776?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Company Logo" class="logo-image" />
        <div class="logo-text">cultivating<br />innovation</div>
      </div>
      <nav class="main-nav">
        <div class="nav-title">
          <span>МЫ СОЗДАЁМ</span>
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/caba460c96b83b7079eb940fe51618fb6ddf3389a3388cbd28bf82c6eb452890?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Navigation Icon" class="nav-icon" />
        </div>
        <ul class="nav-links">
          <li><a href="#about">о компании</a></li>
          <li><a href="#stages">этапы<br />сотрудничества</a></li>
          <li><a href="#faq">FAQ</a></li>
          <li><a href="#contacts">контакты</a></li>
        </ul>
      </nav>
      <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/99d2c27ff9dba93c43e001bf3a922ae36fb0fd5713656333512f2546a982cc22?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Menu Icon" class="menu-icon" />
    </header>
    <main class="main-content">
      <h1 class="page-title">часто задаваемые вопросы</h1>
      <section class="faq-list">
        <div class="faq-item">
          <h2 class="faq-question">С какими регионами вы работаете?</h2>
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/52512e8d69d09d36e26abf35639c64e65937f34c6bc163f677140078dbbe23fd?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Expand Question" class="expand-icon" />
        </div>
        <div class="faq-item">
          <h2 class="faq-question">Сколько длится производство экспозиционного оборудования?</h2>
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/c5ca37ff904b8275e71ea4c29162b23194b121518f1634671cdef02a8c2365f4?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Expand Question" class="expand-icon" />
        </div>
        <div class="faq-item">
          <h2 class="faq-question">Разарабатываете ли вы концепции выставочных экспозиций?</h2>
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/87078a5ab98bb2715495248da085772fd2045c20daf71f180ae5828539811b9d?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Expand Question" class="expand-icon" />
        </div>
        <div class="faq-item">
          <h2 class="faq-question">Существуют ли специальные предложения для корпоративных клиентов?</h2>
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/51366c5f40e672e5108b3b0d8a3ea0ad354c74be2903eccd519aa80e125e7375?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Expand Question" class="expand-icon" />
        </div>
      </section>
      <button class="cta-button">работать с нами</button>
    </main>
    <footer class="footer">
      <div class="footer-info">
        <div class="footer-logo">
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/5ad78a2f3bedb6ed82c306890ec5ba6fc24c4a01eebc3751d613f282dab51abf?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Footer Logo" class="footer-logo-image" />
          <span class="footer-logo-text">cultivating<br />innovation</span>
        </div>
        <p class="company-details">ИНН 780440234137<br />ОГРНИП 320784700280861</p>
        <p class="copyright">Все права защищены © 2024</p>
      </div>
      <div class="footer-nav">
        <nav class="footer-links">
          <ul>
            <li>МЫ СОЗДАЁМ</li>
            <li><a href="#about">о компании</a></li>
            <li><a href="#stages">этапы<br />сотрудничества</a></li>
            <li><a href="#faq">FAQ</a></li>
            <li><a href="#contacts">контакты</a></li>
          </ul>
        </nav>
        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/7797a551acc9f4fbef1622b51a7179db610d895908cbf00358b3d5f867e15d9c?placeholderIfAbsent=true&apiKey=cbb846ea017348448b06f26252bda16b" alt="Social Media Icons" class="social-icons" />
        <p class="contact-info">+7 921 894 67 34<br />Info@cultnova.ru</p>
      </div>
    </footer>
  </div>
</template>

<style scoped>
.faq-page {
  background-color: #fff;
  display: flex;
  flex-direction: column;
  overflow: hidden;
}

.header {
  background-color: #fafafa;
  display: flex;
  width: 100%;
  padding: 22px 44px;
  align-items: center;
  justify-content: space-between;
}

.logo-container {
  display: flex;
  align-items: center;
  gap: 22px;
}

.logo-image {
  width: 140px;
  height: auto;
}

.logo-text {
  color: #475eea;
  text-align: center;
  font: 400 18px/18px 'TT Fors Trial', sans-serif;
}

.main-nav {
  display: flex;
  gap: 28px;
  align-items: center;
}

.nav-title {
  display: flex;
  gap: 13px;
  font-size: 20px;
  font-weight: 700;
}

.nav-icon {
  width: 14px;
  height: auto;
}

.nav-links {
  display: flex;
  gap: 27px;
  font-size: 17px;
  list-style-type: none;
  padding: 0;
}

.nav-links li {
  display: flex;
  align-items: center;
}

.nav-links li::after {
  content: '';
  width: 2px;
  height: 35px;
  background-color: #4e4e4e;
  margin-left: 27px;
}

.nav-links li:last-child::after {
  display: none;
}

.menu-icon {
  width: 29px;
  height: auto;
}

.main-content {
  padding: 186px 116px 0;
}

.page-title {
  color: #000;
  font: 700 50px/1.1 'TT Fors Trial', sans-serif;
  margin-bottom: 111px;
}

.faq-list {
  display: flex;
  flex-direction: column;
  gap: 11px;
}

.faq-item {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 11px 0;
  border-top: 1px solid #525252;
  border-bottom: 1px solid #525252;
}

.faq-question {
  color: #000;
  font: 400 30px/1 'TT Fors Trial', sans-serif;
  margin: 0;
}

.expand-icon {
  width: 67px;
  height: 67px;
}

.cta-button {
  background-color: #475eea;
  border-radius: 75px;
  color: #fff;
  font: 700 27px/1 'TT Fors Trial', sans-serif;
  padding: 27px 70px;
  border: none;
  cursor: pointer;
  align-self: flex-end;
  margin-top: 86px;
  box-shadow: 6px 6px 8px rgba(0, 0, 0, 0.15);
}

.footer {
  background-color: #000;
  color: #fff;
  display: flex;
  justify-content: space-between;
  padding: 39px 71px;
  margin-top: 87px;
}

.footer-info, .footer-nav {
  display: flex;
  flex-direction: column;
}

.footer-logo {
  display: flex;
  align-items: center;
  gap: 18px;
}

.footer-logo-image {
  width: 140px;
  height: auto;
}

.footer-logo-text {
  font-size: 18px;
  line-height: 18px;
}

.company-details {
  margin-top: 39px;
  width: 328px;
}

.copyright {
  margin-top: 64px;
}

.footer-links ul {
  display: flex;
  gap: 26px;
  list-style-type: none;
  padding: 0;
}

.footer-links li {
  font-size: 17px;
  text-align: center;
}

.footer-links li:first-child {
  font-size: 20px;
  font-weight: 700;
}

.social-icons {
  width: 94px;
  height: auto;
  margin-top: 20px;
}

.contact-info {
  font-size: 20px;
  font-weight: 500;
  text-align: right;
  margin-top: 38px;
}

@media (max-width: 991px) {
  .header {
    padding: 22px 20px;
  }

  .main-content {
    padding: 40px 20px 0;
  }

  .page-title {
    font-size: 40px;
    margin-bottom: 40px;
  }

  .cta-button {
    margin-top: 40px;
    padding: 20px 40px;
  }

  .footer {
    flex-direction: column;
    padding: 30px 20px;
    margin-top: 40px;
  }

  .footer-nav {
    margin-top: 30px;
  }
}
</style>