<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Wesley Souza — Perfil</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Custom small tweaks */
    .glass { backdrop-filter: blur(6px); background: rgba(255,255,255,0.06); }
    .accent { background: linear-gradient(90deg,#06b6d4,#7c3aed); }
  </style>
</head>
<body class="min-h-screen bg-gradient-to-b from-gray-900 via-slate-900 to-gray-800 text-gray-100">
  <main class="max-w-5xl mx-auto p-6">
    <header class="grid grid-cols-1 md:grid-cols-3 gap-6 items-center mb-8">
      <div class="md:col-span-2">
        <div class="flex items-center gap-4">
          <div class="w-28 h-28 rounded-full flex items-center justify-center bg-gradient-to-br from-indigo-600 to-cyan-400 shadow-lg">
            <span class="text-3xl font-extrabold">WS</span>
          </div>
          <div>
            <h1 class="text-3xl font-extrabold">Wesley Souza</h1>
            <p class="mt-1 text-cyan-200">Estudante de Engenharia de Software • Python, Dados, Automação & IA</p>
          </div>
        </div>
      </div>

      <div class="flex flex-col items-start md:items-end gap-3">
        <a href="#contato" class="px-4 py-2 rounded-md text-sm font-medium glass border border-slate-700">Contate-me</a>
        <div class="text-sm text-slate-400">E-mail: <a href="mailto:wsdevsoluctions@gmail.com" class="text-cyan-300">wsdevsoluctions@gmail.com</a></div>
      </div>
    </header>

    <section class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
      <div class="md:col-span-2 glass p-6 rounded-2xl">
        <h2 class="text-2xl font-bold mb-3">Sobre mim</h2>
        <p class="text-slate-200 leading-relaxed">Sou um entusiasta da tecnologia que transforma ideias em soluções. Foco em análise de dados, automação e inteligência artificial — sempre buscando criar ferramentas práticas que economizem tempo e entreguem valor real.</p>

        <div class="mt-6 grid grid-cols-1 sm:grid-cols-2 gap-3">
          <div class="p-3 rounded-lg bg-slate-800/40">
            <h3 class="font-semibold">Missão</h3>
            <p class="text-sm text-slate-300">Simplificar processos e resolver problemas do dia a dia com código e IA.</p>
          </div>
          <div class="p-3 rounded-lg bg-slate-800/40">
            <h3 class="font-semibold">Diferencial</h3>
            <p class="text-sm text-slate-300">Combino lógica técnica com foco em usabilidade e impacto humano.</p>
          </div>
        </div>
      </div>

      <aside class="glass p-6 rounded-2xl">
        <h3 class="text-xl font-bold mb-3">Skills</h3>
        <ul class="space-y-2 text-sm text-slate-300">
          <li>Python • Pandas • NumPy</li>
          <li>Java (estudo) • Spring Boot</li>
          <li>SQL • SQLAlchemy • PostgreSQL</li>
          <li>Power BI • Streamlit • Jupyter</li>
          <li>Automação • n8n • Integrações com APIs</li>
        </ul>
      </aside>
    </section>

    <section class="glass p-6 rounded-2xl mb-8">
      <h2 class="text-2xl font-bold mb-3">O que estou aprendendo</h2>
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
        <div class="p-4 rounded-lg bg-slate-800/30">
          <h4 class="font-semibold">ETL & Dados</h4>
          <p class="text-sm text-slate-300">Pipelines com Pandas, limpeza e modelagem de dados.</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-800/30">
          <h4 class="font-semibold">APIs & Automação</h4>
          <p class="text-sm text-slate-300">APIs REST e automações que economizam horas de trabalho manual.</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-800/30">
          <h4 class="font-semibold">IA & Machine Learning</h4>
          <p class="text-sm text-slate-300">Experimentos práticos e modelos simples para resolver problemas concretos.</p>
        </div>
      </div>
    </section>

    <section class="mb-8">
      <h2 class="text-2xl font-bold mb-3">Projetos</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <article class="p-4 rounded-lg glass">
          <h5 class="font-semibold">automacoes-python</h5>
          <p class="text-sm text-slate-300">Scripts para automatizar tarefas do dia a dia.</p>
        </article>
        <article class="p-4 rounded-lg glass">
          <h5 class="font-semibold">etl-dados-pandas</h5>
          <p class="text-sm text-slate-300">Pipeline de tratamento e análise de dados.</p>
        </article>
        <article class="p-4 rounded-lg glass">
          <h5 class="font-semibold">mini-ia</h5>
          <p class="text-sm text-slate-300">Experimentação com IA e modelos iniciais.</p>
        </article>
      </div>
    </section>

    <section id="contato" class="p-6 rounded-2xl accent text-white shadow-lg">
      <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-4">
        <div>
          <h3 class="text-2xl font-bold">Vamos conversar?</h3>
          <p class="mt-1 text-slate-100/90">Estou aberto a projetos, parcerias e oportunidades de aprendizado.</p>
        </div>
        <div class="flex gap-3">
          <a href="mailto:wsdevsoluctions@gmail.com" class="px-4 py-2 rounded-md bg-white text-indigo-700 font-semibold">E-mail</a>
          <a href="#" class="px-4 py-2 rounded-md border border-white/30">LinkedIn</a>
        </div>
      </div>
    </section>

    <footer class="mt-8 text-center text-sm text-slate-400">Feito com ♥ por Wesley Souza — Adaptável para LinkedIn e portfólio.</footer>
  </main>
</body>
</html>
