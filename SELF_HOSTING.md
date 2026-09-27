# Hospedagem própria no GitHub Pages

Esta cópia está pronta para ser publicada em um repositório público chamado
`projetoxdrz`. O endereço resultante será:

`https://system8510.github.io/projetoxdrz/`

O workflow em `.github/workflows/deploy-pages.yml` publica o site automaticamente
a cada envio para a branch `main`.

## Primeira publicação

1. Crie no GitHub um repositório **público** chamado `projetoxdrz`, sem adicionar
   README, licença ou `.gitignore`.
2. Aponte o remote `origin` desta cópia para o novo repositório e envie a branch
   `main`.
3. No repositório do GitHub, abra **Settings > Pages** e selecione
   **GitHub Actions** em **Build and deployment > Source**.
4. Aguarde a action `Deploy to GitHub Pages` terminar.
5. Abra `https://system8510.github.io/projetoxdrz/app/` e clique em
   **Install Userscript**.

O userscript detecta automaticamente o domínio e o caminho da cópia a partir do
endereço de onde foi instalado. Para essa detecção funcionar, mantenha o nome do
repositório como `projetoxdrz` e faça a instalação pelo link do seu próprio Pages.

## Atualizações

O repositório original fica configurado como `upstream`. Para incorporar versões
novas, mescle `upstream/main` e preserve as adaptações desta cópia.

O projeto original e esta cópia permanecem sob a licença GPL-3.0. Mantenha o
arquivo `LICENSE`, os avisos de autoria e disponibilize o código-fonte das suas
alterações.
