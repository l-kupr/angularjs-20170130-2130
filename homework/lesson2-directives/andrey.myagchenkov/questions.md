1) $onChanges вызывается только при изменении переменных в bindings? При изменениях переменных в контроллере этот хук не запускается?

2) По 4-му пункту ДЗ

	4. Сделать фильтрацию писем(custom filter) по полю поиска

	для решения я передал в самописный фильтр весь контроллер. Чувствую что это плохая идея, но не нашел варианта решить иначе. Если есть вариант лучше сообщите пожалуйста

3) По 5-му пункту ДЗ

	5. При удалении элемента(onDestroy) со страницы выводить в консоль сколько "жило письмо" (время создания письма - время когда удалено со страницы).

	index.html - этот пункт выполнен, но через удаление элемента в переменной компонента
	indexWithoutDestroy.html - удаляю узел(компонент) DOM методом remove(), но $onDestroy не запускается  