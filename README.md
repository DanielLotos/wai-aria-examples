# wai-aria-examples
Some rules for WAI-ARIA using

## Когда НЕ использовать WAI-ARIA атрибуты?

Если вы можете использовать нативные HTML-элементы или атрибуты, то используйте их ВМЕСТО WAI-ARIA ролей!

---

## Когда использовать WAI-ARIA атрибуты?

- когда у стандартных тегов HTML нет возможности описать необходимую "фичу"
- если визуальные ограничения не дают использовать необходимый HTML-элемент
- если фичу нельзя реализовать (описать) штатными средствами HTML

---

## Не изменяйте нативную семантику!

❌Плохо
```
<h2 role=tab>heading tab</h2>
```


✅Хорошо
```
<div role=tab>
  <h2>heading tab</h2>
</div>
```
