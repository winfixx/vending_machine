задание делал максимально по тз, из необязательных сделал возможность покупки нескольких напитков перед получением сдачи.
при первом запросе бд иницициализируется с начальным данными. Именно админ с именем Jojo и паролем 12345
(так что тестить админа с него потому что создание нового админа не предусматривал).
писал по чистой архитектуре.
только под конец разработки пришла идея сделать таблицу заказов.
субд postgres
фронт vue, pinia
бек c#, asp net core
орм ef core.

в appsetting на беке: установите UrlClient (url фронта); установите VendingMachineDbContext (строка подключения к субд postgres)
в файле src/consts/base.ts на фронте установите BASE_API_URL (url бека)