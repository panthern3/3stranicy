<template>
    <section class="article mx-auto w-9/12">
      <h1 class="title">Бенуа — идеолог новой художественной эпохи</h1>
      <figure>
        <img src="6.png" alt="">
      </figure>
      <aside class="text-gray-900 text-center text-sm">Источник: Название источника</aside><br>
      <section class="content">
        <p>История и развитие искусства отражает изменения в обществе, культуре и идеологии. Одним из ключевых периодов в истории искусства было начало XX века, когда многие художники стремились выразить новые идеи и переживания через свои работы. В этот период важным фигурой был Василий Кандинский, который выдвинул концепцию абстракционизма. Однако, помимо Кандинского, другим важным историческим фигурой, игравшей ключевую роль в формировании новой художественной эпохи, был Леонид Бенуа.</p><br>
        <article>
          <h1>Жизнь и творчество Леонида Бенуа:</h1>
          <figure>
            <img src="1.png" alt="">
          </figure>
          <aside class="text-gray-900 text-center text-sm">Источник: Название источника</aside><br>
          <p>Биографические данные: Родился в 1856 году в Петербурге, Леонид Бенуа был художником, архитектором, дизайнером, сценографом и педагогом.
          Образование и влияние: Получил классическое художественное образование и был знаком с такими художественными течениями, как символизм и модернизм, которые сильно повлияли на его творчество.
          Работы и достижения: Бенуа работал над различными проектами, включая создание сценографии для театральных постановок, декораций для балетов, а также архитектурных проектов. Его работы отличались изысканностью и символизмом, отражая глубокие философские и эстетические идеи.</p><br>
        </article>
        <article>
          <h1>Идеология новой художественной эпохи:</h1>
          <figure>
            <img src="4.png" alt="">
          </figure>
          <aside class="text-gray-900 text-center text-sm">Источник: Название источника</aside><br>
          <p>Синтез искусств: Бенуа провозглашал идею синтеза различных видов искусства, таких как живопись, скульптура, архитектура и театр. Он считал, что искусство должно быть полностью интегрировано в жизнь человека.
          Символизм и мифология: В работах Бенуа часто встречаются мифологические и символические элементы, которые не только украшают его произведения, но и несут глубокий смысл и эмоциональную нагрузку.
          Эстетика и культура: Бенуа активно исследовал взаимосвязь искусства с культурой и историей, стремясь создать работы, которые были бы не только эстетически привлекательными, но и имели бы глубокий культурный смысл.</p><br>
        </article>
        <article>
          <h1>Наследие и влияние:</h1>
          <figure>
            <img src="8.png" alt="">
          </figure>
          <aside class="text-gray-900 text-center text-sm">Источник: Название источника</aside><br>
          <p>Влияние на современное искусство: Идеи Бенуа о синтезе искусств, использование символизма и глубокого философского подхода оказали значительное влияние на развитие современного искусства.
          Популярность в современной культуре: Работы Бенуа по-прежнему ценятся и изучаются в современном мире, а его идеи продолжают вдохновлять художников и дизайнеров по всему миру.
          Легенда и восприятие: Леонид Бенуа стал символом новаторства и креативности в искусстве, а его имя ассоциируется с началом новой эпохи в художественной и культурной сферах.</p>
        </article>
        <footer>
          <br><h1>Заключение:</h1><br>
          <p class="text-center"><a href="#" @click="scrollToTop" class="text-gray-600 underline">Леонид Бенуа</a> был одним из ключевых фигур в формировании новой художественной эпохи начала XX века. Его идеи о синтезе искусств, использование символизма и глубокий философский подход продолжают оставаться актуальными и влиятельными в современном искусстве. Наследие Бенуа продолжает вдохновлять и мотивировать художников по всему миру, делая его одним из великих идеологов художественного творчества.</p>        </footer>
        </section>
    </section>
  </template>

<script>
export default {
  methods: {
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  }
}
</script>

<style scoped>
.article {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.title {
  font-size: 32px;
  font-weight: bold;
  margin-bottom: 20px;
}

.content {
  font-size: 18px;
  line-height: 1.6;
}

h1 {
  font-size: 32px;
}

aside {
  @apply text-gray-500;
}

img {
  @apply mx-auto;
}

h1 {
  @apply font-bold;
  @apply text-center;
}

p {
  @apply text-gray-800;
}

.title {
  @apply text-blue-900;
}

.content {
  @apply text-gray-700;
}

</style>