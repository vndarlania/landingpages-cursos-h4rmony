# 🎓 Cursos Doutora Gabriela do Vale

Monorepo contendo todos os cursos e landing pages da Dra. Gabriela do Vale.

## 📁 Estrutura do Projeto

```
cursogabi-imersaotoxinabotulinica/
├── apps/                           # Cada curso tem sua própria pasta
│   └── toxina-botulinica/         # Landing page do curso de Toxina Botulínica
│       ├── index.html
│       └── logo.png
├── shared/                         # Componentes compartilhados entre cursos
│   └── (estilos, scripts, assets comuns)
└── README.md
```

## 🚀 Cursos Disponíveis

### 1. Toxina Botulínica
- **Path**: `/toxina-botulinica`
- **Pasta**: `apps/toxina-botulinica/`
- **Status**: ✅ Ativo

## 📦 Como Adicionar um Novo Curso

1. Crie uma nova pasta em `apps/nome-do-curso/`
2. Adicione os arquivos HTML, CSS, JS, imagens, etc.
3. Configure o deploy para o subpath `/nome-do-curso`
4. Atualize este README

## 🌐 Deploy

Cada curso será deployado em:
```
doutora-gabriela.com/toxina-botulinica
doutora-gabriela.com/laser
doutora-gabriela.com/preenchimento
... etc
```

## 📝 Notas

- Cada curso é independente e tem seus próprios arquivos
- A pasta `shared/` pode conter elementos reutilizáveis (header, footer, estilos globais)
- Mantenha cada curso auto-contido em sua pasta
