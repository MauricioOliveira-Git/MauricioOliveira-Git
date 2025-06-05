# 📊 GitHub Readme Stats - MauricioFilho

Visualize estatísticas do seu GitHub com estilo!

Este projeto usa o [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) para exibir informações personalizadas diretamente no seu perfil do GitHub.

## 🧰 Exemplo de Uso

### 🔥 Estatísticas do GitHub

![Estatísticas](https://github-readme-stats-mauriciofilho.vercel.app/api?username=MauricioFilho&show_icons=true&theme=radical)

### 🧠 Linguagens mais usadas

![Linguagens](https://github-readme-stats-mauriciofilho.vercel.app/api/top-langs/?username=MauricioFilho&layout=compact&theme=radical)

---

## 🚀 Deploy na sua própria instância do Vercel

Você pode hospedar sua própria instância do `github-readme-stats` facilmente no [Vercel](https://vercel.com/).

### 📦 Etapas para o Deploy

1. Clique no botão abaixo para fazer o deploy diretamente no Vercel:

   [![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=anuraghazra/github-readme-stats)

2. Após o deploy, vá até **Project Settings > Environment Variables** no Vercel e adicione a seguinte variável de ambiente:

   | Nome da variável       | Valor                                    |
   |------------------------|-------------------------------------------|
   | `PAT_1`                | Seu **GitHub Personal Access Token**     |

   > 🔒 O token é necessário para evitar problemas com *rate limits*. Ele **não** será exposto publicamente.

3. Agora você pode acessar os stats via a URL do seu domínio Vercel. Exemplo:

