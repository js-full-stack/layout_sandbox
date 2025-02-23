# layout_sandbox
aria-label - атрибут для ассистивных технологий
system font stack - системние шрифты для разгрузки системы
row-gap для отступов во флексбоксах

.container {
  display: flex;
  gap: 8px;
  max-width: 960px;
  margin: 0 auto;
}

.sidebar {
  flex-basis: 200px;
}

.content {
  flex-grow: 1;
}

  flex-basis: calc((100% - 20px) / 3);
w