# svelte-capacitor-app

1) npx degit adwiya-deshpande/svelte-capacitor-app my-svelte-capacitor-app
2) cd my-svelte-capacitor-app
3) npm i
4) npm run dev
5) Put these links in the index.html
    <script type="module" src="node_modules/@ionic/core/dist/ionic/ionic.esm.js"></script>
    <script nomodule src="node_modules/@ionic/core/dist/ionic/ionic.js"></script>
    <link rel="stylesheet" href="node_modules/@ionic/core/css/ionic.bundle.css"/>
    
6) To add native platforms , run:
    npx cap add [platform name]
    refer the capacitor docs for this
