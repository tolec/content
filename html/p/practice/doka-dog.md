🛠 Тег `<p>` по факту ведёт себя как обычный блок [`<div>`](/html/div). Нужно учесть, что у `<p>` предустановленно свойства `margin-bottom` и `margin-top` — отступы снизу и сверху, чтобы каждый абзац отступал по умолчанию на 1em (примерно 16 пикселей) от предыдущего. Поэтому этот показатель отступов надо прописывать в CSS для всех тегов `<p>`.

Чтобы сделать заголовок, который не имеет ценности для поисковых машин, то лучше, вместо одного из тегов [`<h1>`...`<h6>`](/html/h1-h6) использовать тег `<p>` с классом `h1` или `h2` и так далее.
