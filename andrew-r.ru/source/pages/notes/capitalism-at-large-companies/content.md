В мою [коллекцию материалов о разработке фронтенда в реальных компаниях](https://github.com/andrew--r/frontend-case-studies) недавно прислали пулреквест с рекомендацией статьи [Free-market software development](http://matt.chadburn.co.uk/notes/teams-as-services.html) Мэтта Чедбёрна из Financial Times (ранее The Guardian и BBC). Я проникся этой статьёй, потому что она совпадает с моими наблюдениями за время работы в Avito.

Во многих крупных компаниях есть отдельные инфраструктурные команды, закрывающие потребности продуктовых команд. Инфраструктурные команды отвечают за базы данных, дизайн-системы, непрерывную интеграцию, developer experience и подобные глобальные штуки. Выглядит здорово — внутри компании есть целые команды, которые готовы закрыть любую потребность продуктовых разработчиков. На практике всё немного сложнее — если всех обязать пользоваться результатом работы инфраструктурных команд, начнутся проблемы.

Навязывание внутренних решений может повлечь за собой демотивацию продуктовых разработчиков и потерю ориентиров у инфраструктурных команд. Продуктовым разработчикам не во всех случаях может подходить внутреннее решение, а отсутствие выбора снижает мотивацию. Инфраструктурные команды выступают в роли монополистов, а без конкуренции развиваться сложнее.

В этом случае приходит на помощь принцип свободного рынка. Нужно дать продуктовым командам свободу выбора технологий и сервисов, тогда они смогут подбирать для своих задач наиболее подходящие решения. В свою очередь, это подстегнёт внутрениие инфраструктурные команды — ведь если все будут пользоваться внешними решениями, во внутренней команде нужды не будет и её расформируют. Это один из основных принципов капитализма: если в условиях свободного рынка люди действуют исходя из личной выгоды, в конечном итоге они приносят пользу всему обществу.

Во второй части статьи Мэтт рассказывает о том, что инфраструктурные команды в таких условиях должны стремиться к уровню SaaS: не просто разрабатывать внутренний продукт, но и продвигать его, документировать, помогать пользователям с проблемами. Отличным примером служит [сервис полифилов Financial Times](https://cdn.polyfill.io/v2/docs/), изначально разработанный для внутренних нужд. Он настолько классно оформлен как продукт, что его сделали доступным снаружи компании и выложили в опенсорс.