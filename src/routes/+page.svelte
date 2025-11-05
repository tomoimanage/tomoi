<script lang="ts">
  export let data: App.PageData;
</script>

<svelte:head>
  <title>{data.seo?.title ?? "TOMOI"}</title>
  <meta name="description" content={data.seo?.description ?? "main page description"} />
</svelte:head>

<h1>{data.seo.title}</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<p>
  국가는 과학기술의 혁신과 정보 및 인력의 개발을 통하여 국민경제의 발전에 노력하여야 한다. 국가는
  건전한 소비행위를 계도하고 생산품의 품질향상을 촉구하기 위한 소비자보호운동을 법률이 정하는 바에
  의하여 보장한다.<br />국가는 농업 및 어업을 보호·육성하기 위하여 농·어촌종합개발과 그 지원등
  필요한 계획을 수립·시행하여야 한다. 국가는 농지에 관하여 경자유전의 원칙이 달성될 수 있도록
  노력하여야 하며, 농지의 소작제도는 금지된다.
</p>
