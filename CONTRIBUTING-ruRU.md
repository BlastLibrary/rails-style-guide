# Как сотрудничать в проекте

Мы очень рады, что вы решили помочь нам в этом проекте! Пожалуйста,
следуйте простым правилам, описанным ниже.

* Сделайте [личную копию][fork] (fork) этого проекта GitHub'е.

* Если вы еще не решили, чем вы можете помочь этому проекту, то просмотрите
  пометки с тегом `@FIXME` в исходном коде. Возможно, что-то из этих пунктов
  покажется вам интересным.

* Если задуманные изменения велики и вызывают сомнения, инициируйте
  [обсуждение][issues] с описанием ваших намерений.

* Создайте тематическую ветку с говорящим именем: `fb_some_important_fix`.
  Не стесняйтесь создать несколько веток для связанных по смыслу изменений:
  принять изменение проще, если оно атомарно, и сложно, если оно велико и
  противоречиво, когда одна часть приветствуется, а другая не совсем.

* При возникновении сомнений в переводе терминов согласуйте свой перевод с
  [глоссарием](https://github.com/arbox/terminology-bank).

* Ссылки на разделы руководства оформляйте на отдельных строках:
```
<a name="english-comments"></a>
Пишите комментарии по-английски.
<sup>[[ссылка](#english-comments)]</sup>
```

* Проделайте запланированную работу по исправлению ошибок или переводу в
  созданной тематической ветке. Прокомментируйте вашу работу при добавлении.

* Пересмотрите содержательность каждого из добавлений (commit), по возможности
  слейте все в один логически атомарное добавление (commit), используйте для
  этого [`git rebase -i ...`][rebase].

* Загрузите вашу ветку на GitHub.

* Отправье нам [запрос на слияние][pull request], добавьте комментарий к нему.

[fork]: https://help.github.com/articles/fork-a-repo
[pull request]: https://help.github.com/articles/using-pull-requests
[issues]: https://help.github.com/articles/about-issues
[rebase]: https://git-scm.com/book/ru/v1/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-Git-%D0%9F%D0%B5%D1%80%D0%B5%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C-%D0%B8%D1%81%D1%82%D0%BE%D1%80%D0%B8%D0%B8
