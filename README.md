

Instação do TYPESCRIPT
npm install typescript@4.2.2 --save-dev

-- CRIAR UM AQR CHAMADO tsconfig.json
inserir: {
    "compilerOptions": {
        "outDir": "dist/js",
        "target": "ES6"
    },
    "include": ["app/**/*"]
}


 -- ADICIONAR SCRIPT
 "compile": "tsc"