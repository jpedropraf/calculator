#  Calculadora de Direitos Trabalhistas  
<p align="center">
  <img src="https://img.icons8.com/fluency/256/calculator.png" width="120" />
</p>

> Uma aplicação moderna para automatizar cálculos de verbas trabalhistas, rescisões, horas extras, FGTS, férias e demais direitos, desenvolvida para advogados, contadores e profissionais do direito.

---

# Tecnologias Utilizadas  
<p align="left">
  <img src="https://img.icons8.com/color/256/react-native.png" width="60" />
  <img src="https://img.icons8.com/color/256/ionic.png" width="60" />
  <img src="https://img.icons8.com/color/256/typescript.png" width="60" />
  <img src="https://img.icons8.com/fluency/256/node-js.png" width="60" />
  <img src="https://img.icons8.com/office/256/express-js.png" width="60" />
  <img src="https://img.icons8.com/color/256/figma.png" width="60" />
  <img src="https://img.icons8.com/color/256/trello.png" width="60" />
</p>

---

# 📄 Descrição do Projeto  

A **Calculadora de Direitos Trabalhistas** foi criada para oferecer uma forma rápida e automatizada de calcular verbas e valores relacionados à CLT.  
Ela substitui planilhas manuais e reduz riscos de erros, facilitando o trabalho de escritórios de advocacia, atendimento a clientes e análises de processos.

Entre os cálculos possíveis:

- Verbas rescisórias  
- FGTS + multa de 40%  
- Horas extras e adicionais  
- Férias + 1/3 constitucional  
- 13º salário integral e proporcional  
- DSR  
- Atualização monetária e juros  
- Indenizações trabalhistas  

#  Prévia do Layout (Figma)

> Imagens ilustrativas

<p align="center">
  <img src="https://placehold.co/800x400?text=HOME" />
</p>

#  Arquitetura do Projeto

```
/project
 ├── app/                        # Frontend (React + Ionic)
 │   ├── src/
 │   │   ├── components/
 │   │   ├── pages/
 │   │   ├── services/
 │   │   └── App.tsx
 │   └── package.json
 │
 ├── backend/                    # Backend (Express + TS)
 │   ├── src/
 │   │   ├── controllers/
 │   │   ├── routes/
 │   │   ├── services/
 │   │   ├── utils/
 │   │   └── server.ts
 │   └── package.json
 │
 ├── README.md
 └── package.json

