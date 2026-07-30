# probable-octo-giggle
{
  "appId": "com.calculadoradeprazos.app",
  "appName": "Calculadora de Prazos",
  "webDir": "dist",
  "bundledWebRuntime": false,
  "server": {
    "androidScheme": "https"
  }
}
<!doctype html>
<html lang="en">
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Google AI Studio App</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <meta name="theme-color" content="#020617" />
    <meta name="description" content="Calculadora de Prazos Processuais e Comerciais (CPC/CLT)" />
    <link rel="manifest" href="/manifest.json" />
    <title>Calculadora de Prazos Processuais</title>
  </head>
  <body>
  <body class="bg-slate-950 text-slate-100">
    <div id="root"></div>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>
{
  "name": "react-example",
  "name": "calculadora-de-prazos",
  "private": true,
  "version": "0.0.0",
  "version": "1.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite --port=3000 --host=0.0.0.0",
    "build": "vite build",
    "preview": "vite preview",
    "clean": "rm -rf dist server.js",
    "lint": "tsc --noEmit"
    "lint": "tsc --noEmit",
    "cap:init": "cap init \"Calculadora de Prazos\" \"com.calculadoradeprazos.app\" --web-dir dist",
    "cap:add": "cap add android",
    "cap:sync": "cap sync android",
    "cap:open": "cap open android"
  },
  "dependencies": {
