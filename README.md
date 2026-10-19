# Rifle Queimada

Projeto Android que transforma o jogo **Rifle Queimada** em um APK instalável.
O jogo fica em `app/src/main/assets/index.html`.

## Como gerar o APK no GitHub

1. Crie um repositório novo no GitHub (pode ser privado).
2. Envie **todos** os arquivos desta pasta para o repositório, inclusive a pasta `.github`.
3. Abra a aba **Actions** do repositório. A tarefa **Gerar APK** começa sozinha a cada envio.
   Se ela não aparecer, clique em **Gerar APK** e depois em **Run workflow**.
4. Espere ficar verde (leva uns 3 a 5 minutos).
5. Clique na execução concluída e baixe **rifle-queimada-apk** em *Artifacts*.
   Dentro do .zip baixado está o arquivo `rifle-queimada.apk`.

## Como instalar no celular

1. Passe o `rifle-queimada.apk` para o celular Android.
2. Abra o arquivo e permita "instalar apps de fontes desconhecidas" quando o celular pedir.
3. Toque em **Instalar**.

## Para atualizar o jogo

Troque o arquivo `app/src/main/assets/index.html` pela versão nova, aumente
`versionCode` em `app/build.gradle` (por exemplo de 1 para 2) e envie de novo.
