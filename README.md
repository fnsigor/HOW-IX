 <h1>Instalando e executando o projeto</h1>

  <p>Mobile:</p>
  <ul>
    <li><code>npm i</code></li>
    <li><code>npx expo start</code></li>
  </ul>

  <blockquote>
    O projeto mobile foi feito com o expo 51. Para instalá-lo, acesse o link
    <a href="https://expo.dev/changelog/2024-05-07-sdk-51"
      target="_blank">https://expo.dev/changelog/2024-05-07-sdk-51</a>
  </blockquote>

  <blockquote>
    Em <code>/mobile/server/api.ts</code>, o link de baseURL deve ser da máquina local, uma vez que o app não
    consegue acessar localhost diretamente. No windows, para acessar o ip da máquina, execute o comando
    <code>ipconfig</code>
  </blockquote>

  <p>Server:</p>
  <ul>
    <li><code>npm i</code></li>
    <li><code>npm run dev</code></li>
    <li><code>o servidor estará rodando na porta :3333</code></li>
  </ul>
