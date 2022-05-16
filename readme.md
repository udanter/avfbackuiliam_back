# Iniciando o Projeto #
1.  yarn init -y     ..................... cria o package.json
2.  yarn add typescript -D    ............ cria node_modules e yarn.lock
3.  yarn tsc --init    ................... cria tsconfig.json

4.  Alterar o tsconfig.json
{
  "compilerOptions": {
    "target": "ES2020",  
    "module": "commonjs",  
    "rootDir": "./src", 
    "outDir": "./dist",
    "esModuleInterop": true, 
    "forceConsistentCasingInFileNames": true,  
    "strict": true,                                  
    "skipLibCheck": true                                
  }
}

5.  Criar a pasta "src"
6.  index.ts

7.  yarn add express cors

8.  yarn add @types/node @types/typescript @types/express @types/cors ts-node-dev -D

9. *****{}Package.json
},
  "scripts": {
    "dev": "ts-node-dev --respawn --transpile-only ./src/index.ts",
    "build": "tsc",
    "start": "node ./dist"
  }
}

10.  yarn dev ............. para rodar o código


# GIT # // GIT => versionador (repositório)
11. abrir o Git Bash

12. usar o comando:  git config --global user.name "Uiliam Danter"

13. usar o comando:  git config --global user.email "udanter@gmail.com"

14. usar o comando: git config --list




# GitHub - Primeira Vez # // GITHUB => plataforma

15. criar o .gitignore ............... para ignorar a pasta node_modules

16. criar repositório github (avf_back_uiliam.git)

17. git init (para iniciar repositório)

18. git add .

19. git commit -m "Iniciando Projeto AVF-BACK"

20. git remote add origin ... ( pegar no github )

21. git push ( pegar comando completo na mensagem )

# GitHub - Demais Vezes #

22. git add .

23. git commit -m "Iniciando Projeto AVF-BACK"

24. git push