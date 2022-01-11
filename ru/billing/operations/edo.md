# Подключиться к электронному документообороту

После того как вы подключитесь к ЭДО, {{ yandex-cloud }} перестанет отправлять:
* электронные версии закрывающих документов на электронную почту;
* оригиналы закрывающих документов Почтой России на физический адрес.

Подробнее о том, [какие документы можно получать по ЭДО](../concepts/edo.md#document).

{{ yandex-cloud }} сотрудничает по ЭДО только с юридическими лицами и индивидуальными предпринимателями (ИП), которые являются резидентами РФ.

## Подключитесь к ЭДО {#connect}

Чтобы начать сотрудничество по ЭДО с {{ yandex-cloud }}:

1. Подключитесь к [оператору](../concepts/edo.md#operator) ЭДО — [Диадок (СКБ Контур)](https://www.diadoc.ru/) или [СБИС (Тензор)](https://sbis.ru/). Инструкцию по подключению можно найти на сайте оператора. {{ yandex-cloud }} не работает с другими операторами и не поддерживает роуминг.

1. Подпишите соглашение от {{ yandex-cloud }} в личном кабинете ЭДО.

    {% note info %}

    Чтобы быстрее получить соглашение, [заполните форму](https://forms.yandex.ru/surveys/10035776.0ccf604a1212deccbba466c182a895d369193f38/), указав ИНН, КПП организации и наименование используемого оператора ЭДО.

    {% endnote %}

    {{ yandex-cloud }} отправляет соглашения для подключения к ЭДО два раза в месяц (с 10 по 13 и с 25 по 28 число), если вы:
    * пользуетесь услугами {{ yandex-cloud }} и за последние полгода для вас был сформирован хотя бы один [акт](../concepts/act.md);
    * подключены к оператору ЭДО [Диадок (СКБ Контур)](https://www.diadoc.ru/) или [СБИС (Тензор)](https://sbis.ru/);
    * еще не подписывали соглашение от {{ yandex-cloud }}.

После подписания соглашения вы начнете получать документы от {{ yandex-cloud }}. Это документы, сформированные не ранее даты доставки подписанного соглашения во внутренний ИТ-сервис ЭДО. Они будут автоматически отправляться через ЭДО в сроки, которые указаны в договоре на оказание услуг.

Оригиналы документов, сформированных до подписания соглашения, отправляются только Почтой России на физический адрес.

Информацию о подписантах соглашения с принимающей стороны можно найти в личном кабинете оператора. Если информацию найти не удается, обратитесь в техническую поддержку оператора.

{{ yandex-cloud }} не обрабатывает вопросы из личного кабинета оператора. Если у вас есть вопрос, отправьте письмо на [ops_tasks@yandex-team.ru](mailto:ops_tasks@yandex-team.ru). Мы ответим в течение 3-5 рабочих дней.