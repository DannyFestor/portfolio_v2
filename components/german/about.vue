<template>
  <section
    id="about"
    ref="about"
    class="relative flex min-h-screen w-full flex-col lg:flex-row"
  >
    <img
      src="~/assets/danny.jpg"
      alt="This is me"
      class="absolute top-0 left-0 h-screen object-cover opacity-30"
    />
    <article
      class="relative flex flex-1 flex-col items-center justify-center gap-4 px-8"
    >
      <h2 class="pb-4 text-center text-2xl uppercase">Hi, ich bin Danny!</h2>
      <h1 class="py-4 text-center text-4xl font-bold">
        Ich erstelle <strong>moderne Webseiten</strong>
      </h1>
      <p class="text-center text-xl">
        Ich benutze <em>moderne Technologien</em> um den Traum Ihrer Webseite zu
        verwirklichen.
      </p>
      <p class="text-center text-xl">
        Webseiten und Lösungen nach Maß, nicht aus der Dose.
      </p>
      <p class="text-center text-xl">
        Webseiten, so individuell wie Ihre Ideen.
      </p>

      <AboutServiceCard class="mt-24">
        <template #header> Sichere Web-Services </template>
        <div>
          Mit modernen Technologien entwickle ich sichere Anwendungen, die Ihren
          Ansprüchen garantiert genügen.
        </div>
      </AboutServiceCard>
      <AboutServiceCard>
        <template #header> Schnelle Web-Seiten </template>
        <div>
          Browser müssen nicht langsam sein. Der Einsatz moderne
          JavaScript-Frameworks garantiert sichere und schnelle Seiten.
        </div>
      </AboutServiceCard>
    </article>
  </section>
</template>
