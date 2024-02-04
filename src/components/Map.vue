<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>오시는 길</h3>
      <div class="uk-accordion-content">
        <p>
          <span class="header-text">토평동 다목적회관</span><br />
          <span class="content-text"
            >제주도 서귀포시 토평로50번길 4</span
          >
        </p>
        <div>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3335.8379972553716!2d126.58770927684911!3d33.27073327346136!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x350c54bfaad39fe9%3A0xcd9b2b2b6903f06c!2s4%20Tosang-ro%2C%20Seogwipo%2C%20Jeju-do!5e0!3m2!1sen!2skr!4v1707058852237!5m2!1sen!2skr"
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
