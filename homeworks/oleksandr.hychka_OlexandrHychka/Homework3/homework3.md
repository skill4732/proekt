## Homework №3

*Клас*: Телефон

*Об'єкт*: Мій мобільний телефон

*Наслідування*: Мобільний телефон -> Смартфон

*Інкапсуляція*: Користувачу не потрібно знати що саме відбувається в телефоні для того щоб здійснити дзвінок, написати повідомлення etc.

*Поліморфізм*: В залежності від типу телефону, стандарти які він підтримує і оператора стільникового зв'язку зв'язок може здійснюється через різні типи мереж - 2G, 3G WCDMA, 3G CDMA, LTE etc. в той же час не залежно через які стандарти працює телефон всі вони здійснюють з'єднання між двома (або більше) пристроями


**SOLID**

*Single responsibility*
Іконка додатку - слугує для запуску додатку конкретного додатку

*Open-closed*

Ми можемо розширити об'єм пам'яті телефону за допомогою флеш карти. Однак ми не можимо модифікувати об'єм внутрішньої пам'яті пристрою

*Liskov substitution*

Смартфон може відтворювати аудіо файли через навушники підключені до нього через джек 3,5. Дротові наушники можна замінити на бездротові навушники, при цьому програвання аудіофайлу буде можливим і надалі

*Interface segregation*

В телефоні для кожної дії існує свій окермий інтерфейс - менеджер встановлення додатків, телефонна книга, додаток для роботи з камерою і etc.

*Dependency Invertion*

Встановлені програми не повинні впливати на роботу смартфона. Програми перебувають в залежаності від Операційної системи телефону. Операційна ситема телефону впливає на його функціонування. 
