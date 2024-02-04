<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>오시는 길</h3>
      <div class="uk-accordion-content">
        <p>
          <span class="header-text">빌라드지디 청담</span><br />
          <span class="content-text"
            >서울시 강남구 학동로 519</span
          >
        </p>
        <p>
          <span class="content-text"><span class="uk-label uk-label-success">7호선</span>
          청담역 12번 출구 바로 앞 위치</span><br/>
          <span class="content-text"><span class="uk-label uk-label-success">버스</span>
          청담역, 경기고교(진흥아파트 방면) 정류장 하차<br /> (버스번호 301, 401, 2415, 3414, 3426, 4419번)</span><br/>
          <span class="content-text"><span class="uk-label uk-label-success">자가용</span>
          서울특별시 강남구 학동로 519<br />(서울특별시 강남구 펑담동 73-4번지)</span>
        </p>
        <div>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3164.481259735884!2d127.05286187697763!3d37.52015117205076!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357ca5419460f02b%3A0xc83d0b0bd4ba3c31!2sVILLA%20DE%20GD%20CHUNGDAM!5e0!3m2!1sen!2skr!4v1707057944137!5m2!1sen!2skr"
            width="100%"
            height="300"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.header-text {
  color: #ffffffd0;
  font-weight: 600;
}

.uk-label {
  font-size: 0.8rem;
  padding: 0 5px;
  border-radius: 10px;
  vertical-align: inherit;
  margin: 0 5px 0 0;
}
</style>
