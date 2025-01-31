# PHP. Дорожная карта

Если у Вас есть такая возможность и Вы хотите отблагодарить автора за работу - воспользуйтесь следующей ссылкой:

https://www.buymeacoffee.com/maxdzhan

---------------------------------------------------------------------------

## [Дорожная карта бекенд-разработчика](https://roadmap.sh/backend)
## [Самоучитель по компьютерным наукам](https://github.com/ossu/computer-science)
## [Список PHP библиотек, ресурсов и т.д. для решения различных задач, сгруппированный по темам](https://github.com/ziadoz/awesome-php)

---------------------------------------------------------------------------

## Что такое Backend-разработка?

Backend-разработка — это часть веб-разработки, которая касается серверной части веб-приложения. Сюда входит создание и управление серверной логикой, подключение приложения к базе данных, создание серверных API, реализация аутентификации и авторизации пользователей, а также обработка и ответ на запросы пользователей. Это часто предполагает использование таких языков программирования, как Python, Java, Ruby, PHP, JavaScript (Node.js) и .NET.

## Чем занимается Backend-разработчик?

Backend-разработчик отвечает за разработку серверных компонентов веб-приложения:
* работу с базами данных;
* обработку запросов;
* создание серверных API, которые могут использоваться фронтэнд-разработчиками для извлечения и манипулирования данными;
* обеспечение масштабируемости систем, т.е. он должен убедиться, что серверная часть может обрабатывать большой объем трафика и является производительной;
* интегрирование внешних сервисов, такие как платежные шлюзы, очереди сообщений, облачные сервисы и т. д.

## Интернет
### Как работает интернет?

Интернет представляет собой глобальную сеть компьютеров, соединенных друг с другом и обменивающихся данными посредством стандартизированного набора протоколов.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82)
* [Как работает Интернет](https://developer.mozilla.org/ru/docs/Learn/Common_questions/How_does_the_Internet_work)
* [How does the Internet Work?](https://cs.fyi/guide/how-does-internet-work)
* [The Internet Explained](https://www.vox.com/2014/6/16/18076282/the-internet)
* [How Does the Internet Work?](http://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
* [Introduction to Internet](https://roadmap.sh/guides/what-is-internet)
* [How does the Internet work?](https://www.youtube.com/watch?v=x3c1ih2NJEg)
* [How the Internet Works in 5 Minutes](https://www.youtube.com/watch?v=7_LPdttKXPc)

### Что такое HTTP?

HTTP – это протокол прикладного уровня на основе `TCP/IP`, который стандартизирует взаимодействие клиента и сервера друг с другом. Он определяет, как контент запрашивается и передается через Интернет.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/HTTP)
* [Everything you need to know about HTTP](https://cs.fyi/guide/http-in-depth)
* [What is HTTP?](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)
* [Full HTTP Networking Course](https://www.youtube.com/watch?v=2JYT5f2isg4)
* [An overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
* [HTTP/3 From A To Z: Core Concepts](https://www.smashingmagazine.com/2021/08/http3-core-concepts-part1/)
* [HTTP/1 to HTTP/2 to HTTP/3](https://www.youtube.com/watch?v=a-sBfyiXysI)
* [HTTP Crash Course & Exploration](https://www.youtube.com/watch?v=iYM2zFP3Zn0)

### Что такое браузер и как он работает

Веб-браузер – это программное приложение, которое позволяет пользователю получать доступ и отображать веб-страницы или другой онлайн-контент через свой графический пользовательский интерфейс.

Полезные ссылки:

* [Как работают браузеры](https://developer.mozilla.org/ru/docs/Web/Performance/How_browsers_work)
* [How Browsers Work](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
* [Role of Rendering Engine in Browsers](https://www.browserstack.com/guide/browser-rendering-engine)

### DNS и как они работают

Система доменных имен (DNS) – это телефонная книга Интернета. Пользователи получают доступ к информации в Интернете через доменные имена, например, nytimes.com или espn.com. Веб-браузеры, напротив, взаимодействуют через IP-адреса. DNS переводит доменные имена в IP-адреса, чтобы браузеры могли загружать интернет-ресурсы.

Полезные ссылки:

* [Что такое DNS?](https://aws.amazon.com/ru/route53/what-is-dns/)
* [What is DNS? | How DNS works](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
* [How DNS works (comic)](https://howdns.works/)
* [Understanding Domain names](https://developer.mozilla.org/en-US/docs/Glossary/DNS/)
* [DNS and How does it Work?](https://www.youtube.com/watch?v=Wj0od2ag5sk)
* [DNS Records](https://www.youtube.com/watch?v=7lxgpKh_fRY)
* [Complete DNS mini-series](https://www.youtube.com/watch?v=zEmUuNFBgN8&list=PLTk5ZYSbd9MhMmOiPhfRJNW7bhxHo4q-K)

### Что такое доменные имена

Доменное имя – это уникальный, легко запоминающийся адрес, используемый для доступа к веб-сайтам, таким как «google.com» и «facebook.com». Пользователи могут подключаться к веб-сайтам, используя доменные имена, благодаря системе DNS.

Полезные ссылки:

* [Что такое доменные имена](https://developer.mozilla.org/ru/docs/Learn/Common_questions/What_is_a_domain_name)
* [What is a Domain Name? | Domain name vs. URL](https://www.cloudflare.com/en-gb/learning/dns/glossary/what-is-a-domain-name/)
* [A Beginners Guide to How Domain Names Work](https://www.youtube.com/watch?v=Y4cRx19nhJk)

### Что такое хостинг?

Веб-хостинг – это онлайн-сервис, который выдаёт файлы вашего веб-сайта в Интернете. Таким образом, любой, кто имеет доступ к Интернету, имеет доступ к вашему сайту.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%A5%D0%BE%D1%81%D1%82%D0%B8%D0%BD%D0%B3)
* [What Is Web Hosting? Explained](https://www.youtube.com/watch?v=htbY9-yggB0)
* [Different Types of Web Hosting Explained](https://www.youtube.com/watch?v=AXVZYzw8geg)
* [Where to Host a Fullstack Project on a Budget](https://www.youtube.com/watch?v=Kx_1NYYJS7Q)
* [What is the difference between webpage, website, web server, and search engine?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines)
* [What is a web server?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server)

## Базовые знания из фронтенд разработки
### HTML

HTML (**H**yper**T**ext **M**arkup **L**anguage – «язык гипертекстовой разметки») – стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.

Элементы HTML являются строительными блоками HTML страниц. С помощью HTML разные конструкции, изображения и другие объекты, такие как интерактивная веб-форма, могут быть встроены в отображаемую страницу. HTML предоставляет средства для создания заголовков, абзацев, списков, ссылок, цитат и других элементов. Элементы HTML выделяются тегами, записанными с использованием угловых скобок. Такие теги, как `<img />` и `<input />`, напрямую вводят контент на страницу. Другие теги, такие как `<p>`, окружают и оформляют текст внутри себя и могут включать другие теги в качестве подэлементов. Браузеры не отображают HTML-теги, но используют их для интерпретации содержимого страницы.

Язык XHTML является более строгим вариантом HTML, он следует синтаксису XML и является приложением языка XML в области разметки гипертекста.

В HTML можно встроить программный код на языке программирования JavaScript, для управления поведением и содержанием веб-страниц. Также включение CSS в HTML позволяет задавать внешний вид и макет страницы.

Полезные ссылки:

* [HTML Introduction](https://www.w3schools.com/html/html_intro.asp)
* [HTML](https://ru.wikipedia.org/wiki/HTML)

### CSS

CSS (**C**ascading **S**tyle **S**heets – «каскадные таблицы стилей») – формальный язык декорирования и описания внешнего вида документа (веб-страницы), написанного с использованием языка разметки (чаще всего HTML или XHTML). Также может применяться к любым XML-документам, например, к SVG или XUL.

Полезные ссылки:

* [CSS](https://ru.wikipedia.org/wiki/CSS)
* [CSS Introduction](https://www.w3schools.com/css/css_intro.asp)

### Javascript

JavaScript – мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили. Является реализацией спецификации ECMAScript (стандарт ECMA-262).

JavaScript обычно используется как встраиваемый язык для программного доступа к объектам приложений. Наиболее широкое применение находит в браузерах как язык сценариев для придания интерактивности веб-страницам.

Полезные ссылки:

* [Javascript](https://ru.wikipedia.org/wiki/JavaScript)
* [JavaScript Introduction](https://www.w3schools.com/js/js_intro.asp)
* [Современный учебник JavaScript](https://learn.javascript.ru/)

### Смотри также [дорожную карту фронтенд разработчика](https://roadmap.sh/frontend)

## ОС и общие знания

Операционная система – это программа, которая управляет ресурсами компьютера, особенно распределением этих ресурсов между другими программами. Примерами ресурсов могут быть центральный процессор (ЦП), память компьютера, хранилище файлов, устройства ввода/вывода (I/O) и сетевые подключения.

Полезные ссылки:

* [What is an operating system?](https://edu.gcfglobal.org/en/computerbasics/understanding-operating-systems/1/)
* [Operating System summary](https://www.guru99.com/os-tutorial.html)
* [Operating Systems: Crash Course Computer Science #18](https://www.youtube.com/watch?v=26QPDBe-NB8&ab_channel=CrashCourse)
* [Introduction to Operating System](https://www.youtube.com/watch?v=vBURTt97EkA&list=PL9hkZBQk8d1zEGbY7ShWCZ2n1gtxqkRrS&index=1)

### Использование терминала

Терминал (командная строка или консоль) позволяет нам выполнять и автоматизировать задачи на компьютере без использования графического пользовательского интерфейса.

Полезные ссылки:

* [Terminal Usage](https://www.cs.cmu.edu/~15131/f17/topics/terminal-usage/)
* [Command line crash course](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line)
* [Basic Terminal Usage – Cheat Sheet to make the command line EASY](https://www.youtube.com/watch?v=jDINUSK7rXE)

#### Базовые команды терминала

Работать в терминале любому Backend-разработчику приходится практически ежедневно. Существует множество команд и утилит, которые могут помочь вам более эффективно выполнять свои задачи.

Лучший способ выучить эти команды – попрактиковаться с их использованием на своем компьютере/в локальной среде разработки. Обратите внимание на те, которые связаны с командами/утилитами Linux, являющейся наиболее распространенной ОС в отрасли.

Чтобы понять как работают эти команды, прочитайте соответствующие страницы документации и руководств по эксплуации, используя команду man, например, `man grep`, `man awk` и т. д.

Потратив определенное время на теорию и практику, вам станет намного проще использовать эти команды.

* [grep](https://www.geeksforgeeks.org/grep-command-in-unixlinux/),
* [awk](https://www.geeksforgeeks.org/awk-command-unixlinux-examples/),
* [sed](https://www.geeksforgeeks.org/sed-command-in-linux-unix-with-examples/),
* [lsof](https://www.geeksforgeeks.org/lsof-command-in-linux-with-examples/), 
* [curl](https://www.geeksforgeeks.org/curl-command-in-linux-with-examples/),
* [wget](https://linuxize.com/post/wget-command-examples/), 
* [tail](https://www.geeksforgeeks.org/tail-command-linux-examples/), 
* [head](https://www.geeksforgeeks.org/head-command-linux-examples/), 
* [less](https://www.geeksforgeeks.org/less-command-linux-examples/), 
* [find](https://www.geeksforgeeks.org/find-command-in-linux-with-examples/), 
* [ssh](https://www.ssh.com/academy/ssh/command), 
* [kill](https://www.geeksforgeeks.org/kill-command-in-linux-with-examples/)
* [dig](https://www.geeksforgeeks.org/dig-command-in-linux-with-examples/)

Полезные ссылки:

* [Command line crash course](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line)
* [40 Basic Linux Commands](https://www.hostinger.com/tutorials/linux-commands)
* [A collection of modern/faster/saner alternatives to common unix commands](https://github.com/ibraheemdev/modern-unix)
* [Command Line Tutorial](https://www.learnenough.com/command-line-tutorial)
* [Commandline Challenge](https://cmdchallenge.com/)
* [The 50 Most Popular Linux & Terminal Commands (with timestamps)](https://www.youtube.com/watch?v=ZtqBQ68cfJc)

### Общий принцип работы ОС

Операционная система – это основная программа на компьютере, которая управляет всеми другими приложениями. Она позволяет использовать браузеры, играть в игры, распечатывать документы, запускать любимую программу.

Полезные ссылки:

* [What is an operating system?](https://edu.gcfglobal.org/en/computerbasics/understanding-operating-systems/1/)
* [Operating System – Overview](https://www.tutorialspoint.com/operating_system/os_overview.htm)
* [Operating System Concepts](https://codex.cs.yale.edu/avi/os-book/OS10/index.html)
* [Operating System Basics](https://www.youtube.com/watch?v=9GDX-IyZ_C8)

### Управление процессами

Управление процессами включает в себя различные задачи, такие как создание, диспетчеризация, завершение процессов и решение проблем, связанных с 
взаимной блокировкой. Процесс – это программа, исполняемая в настоящий момент. Он является важной частью современных операционных систем. ОС должна выделять ресурсы, которые позволяют процессам совместно использовать информацию и обмениваться ею. Она также защищает ресурсы каждого процесса 
друг от друга и обеспечивает их синхронизацию.

Полезные ссылки:

* [Processes and Process Management](https://www.omscs-notes.com/operating-systems/processes-and-process-management/)
* [Operating System: Process and Process Management](https://medium.com/@akhandmishra/operating-system-process-and-process-management-108d83e8ce60)
* [Process Management in OS: PCB in Operating System](https://www.guru99.com/process-management-pcb.html)

### Потоки и многопоточность

Поток выполнения – это наименьшая единица обработки, которая может быть выполнена в ОС. В большинстве современных операционных систем поток существует внутри процесса, то есть один процесс может содержать несколько потоков.

Многопоточность характеризуется одновременным выполнением нескольких потоков. Такое происходит в операционной системе, когда несколько потоков процессов выполняются одновременно. Эти потоки могут взаимодействовать друг с другом через общую память или передачу сообщений. Многопоточность приводит к совместному использованию ресурсов, что вызывает такие проблемы, как взаимоблокировки и нехватка ресурсов. Они решаются такими методами, как координация процессов, выделение памяти и планирование выполнения процессов, чтобы максимизировать пропускную способность.

Полезные ссылки:

* [Threads And Concurrency](https://www.omscs-notes.com/operating-systems/threads-and-concurrency/)
* [What’s the Diff: Programs, Processes and Threads](https://www.backblaze.com/blog/whats-the-diff-programs-processes-and-threads/)
* [Concurrency in Operating System](https://www.javatpoint.com/concurrency-in-operating-system)
* [Intro to Processes & Threads](https://www.youtube.com/watch?v=exbKr6fnoUw)
* [Introduction to Concurrency](https://www.youtube.com/watch?v=iKtvNJQoCNw)
* [Concurrency, Threading and Parallelism Explained](https://www.youtube.com/watch?v=olYdb0DdGtM)

### Управление памятью

Термин "Память" можно определить как набор данных в определенном формате. Она используется для хранения команд и обработки данных. Память состоит из большого массива или группы байтов, каждый из которых имеет свой собственный адрес. Основной задачей компьютерной системы является выполнение программ.
Эти программы вместе с информацией, к которой они обращаются, во время выполнения должны находиться в оперативной памяти. ЦП извлекает команды из памяти в соответствии со значением счетчика команд.

Для достижения определенной степени многозадачности и правильного использования памяти важно управление памятью. Существует несколько методов управления памятью, отражающих различные подходы, и эффективность каждого алгоритма зависит от ситуации.

Полезные ссылки:

* [Memory Management](https://www.omscs-notes.com/operating-systems/memory-management/)
* [Demystifying memory management in modern programming languages](https://dev.to/deepu105/demystifying-memory-management-in-modern-programming-languages-ddd)
* [Memory Management in Operating System](https://www.geeksforgeeks.org/memory-management-in-operating-system/)

### Межпроцессное взаимодействие

Межпроцессное взаимодействие (IPC) относится конкретно к механизмам, которые предоставляет операционная система, позволяющим процессам управлять общими данными.

Полезные ссылки:

* [Inter-Process Communication](https://www.omscs-notes.com/operating-systems/inter-process-communication/)
* [Interprocess Communication](https://www.geeksforgeeks.org/inter-process-communication-ipc/)
* [Interprocess Communication – Neso Academy](https://www.youtube.com/watch?v=dJuYKfR8vec)

### Управление вводом/выводом

Одной из важных задач операционной системы является управление различными устройствами ввода-вывода, включая мышь, клавиатуру, сенсорную панель, дисковые и твердотельные накопители, адаптеры дисплея, USB-устройства, экраны с растровым отображением, светодиоды, аналого-цифровые преобразователи, коммутаторы, сетевые подключения, аудиовходы/выходы, принтеры и т. д.

Полезные ссылки:

* [IO Management](https://www.omscs-notes.com/operating-systems/io-management/)
* [Operating System – I/O Hardware](https://www.tutorialspoint.com/operating_system/os_io_hardware.htm)
* [Basics of OS (I/O Structure)](https://www.youtube.com/watch?v=F18RiREDkwE)

### Основы POSIX (stdin, stdout, stderr, pipes)

POSIX (Portable Operating System Interface – переносимый интерфейс операционных систем) – это набор стандартов для обеспечения совместимости между операционными системами. В нём описываются утилиты, API и службы, которые совместимая ОС должна предоставлять программному обеспечению, что упрощает перенос программ из одной системы в другую.

Практический пример: в Unix-подобной операционной системе существует три **стандартных потока**, `stdin`, `stdout` и `stderr` — это подключения ввода/вывода, с которыми вы, вероятно, столкнетесь при использовании терминала, поскольку они управляют потоком из *стандартного ввода* (stdin), *стандартного вывода* (stdout) и *стандартной ошибки* (stderr).

Таким образом, когда мы хотим взаимодействовать с любым из этих потоков (например, через процесс), API POSIX операционной системы позволяет упростить этот процесс — например, в библиотеке на языке C `<unistd.h>` stdin, stderr и stdout определены как `STDIN_FILENO`, `STDERR_FILENO` и `STDOUT_FILENO`.

POSIX также внедряет стандарт для кодов завершения программы, семантики файловой системы и нескольких других общепринятых API соглашений для утилит командной строки.

Полезные ссылки:

* [Стандартные потоки](https://ru.wikipedia.org/wiki/%D0%A1%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D1%8B%D0%B5_%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8)
* [Pipes](https://sodocumentation.net/posix/topic/8082/pipes)
* [POSIX standard by IEEE](https://pubs.opengroup.org/onlinepubs/9699919799/)
* [Summary of some POSIX implementations](https://unix.stackexchange.com/a/220877)
* [A guide to POSIX](https://www.baeldung.com/linux/posix)

### Основные прицнипы работы компьютерной сети

Компьютерная сеть представляет собой связанные друг с другом вычислительные устройства, которые могут обмениваться данными и совместно использовать ресурсы. Устройства, входящие в сеть, используют систему правил (коммуникационные протоколы), для передачи информации с помощью физических или беспроводных технологий.

Полезные ссылки:

* [Basic Networking Concepts-Beginners Guide](http://www.steves-internet-guide.com/networking/)
* [What is Computer Networking?](https://aws.amazon.com/what-is/computer-networking/)

---------------------------------------------------------------------------

1. Эндрю С. Таненбаум Современные операционные системы: [пер. с англ.]: Питер, 2011.

## Основы языка PHP

Главная область применения PHP – написание скриптов, работающих на стороне сервера; таким образом, PHP способен выполнять все то, что выполняет любая другая программа CGI, например, обрабатывать данные форм, генерировать динамические страницы или отсылать и принимать cookies.

PHP доступен для большинства операционных систем, включая Linux, многие модификации Unix (такие как HP-UX, Solaris и OpenBSD), Microsoft Windows, macOS, RISC OS и многие другие. Также в PHP включена поддержка большинства современных веб-серверов, таких как Apache, IIS и многих других. В принципе, подойдёт любой веб-сервер, способный использовать бинарный файл FastCGI PHP, например, lighttpd или nginx. PHP может работать в качестве модуля или функционировать в качестве процессора CGI.

Таким образом, выбирая PHP, вы получаете свободу выбора операционной системы и веб-сервера. Более того, у вас появляется выбор между использованием процедурного или объектно-ориентированного программирования (ООП) или же их сочетания.

Полезные ссылки:

* [Возможности PHP](https://www.php.net/manual/ru/intro-whatcando.php)

### Основы синтаксиса

Когда PHP обрабатывает файл, он ищет открывающие и закрывающие теги, такие как <?php и ?>, которые указывают PHP, когда начинать и заканчивать обработку кода между ними. Подобный способ обработки позволяет PHP внедряться во все виды различных документов, так как всё, что находится вне пары открывающих и закрывающих тегов, будет проигнорировано парсером PHP.

Все, что находится вне пары открывающегося и закрывающегося тегов, игнорируется интерпретатором PHP, у которого есть возможность обрабатывать файлы со смешанным содержимым. Это позволяет PHP-коду быть встроенным в документы HTML, к примеру, для создания шаблонов.

Как в C или Perl, PHP требует окончания инструкций точкой запятой в конце каждой инструкции. Закрывающий тег блока PHP-кода автоматически применяет точку с запятой; т.е. нет необходимости ставить точку с запятой в конце последней строки блока с PHP-кодом. Закрывающий тег блока "поглотит" немедленно следующий за ним переход на новую строку, если таковой будет обнаружен.

PHP поддерживает комментарии в стиле 'C', 'C++' и оболочки Unix (стиль Perl). Однострочные комментарии идут только до конца строки или текущего блока PHP-кода, в зависимости от того, что идёт перед ними. Это означает, что HTML-код после // ... ?> или # ... ?> БУДЕТ напечатан: ?> завершает режим PHP и возвращает режим HTML, а // или # не могут повлиять на это. 'C'-комментарии заканчиваются при первой же обнаруженной последовательности */.

Полезные ссылки:

* [Основы синтаксиса](https://www.php.net/manual/ru/language.basic-syntax.php)

### Типы данных

У каждого выражения в PHP один из следующих встроенных типов в зависимости от его значения:

* null
* bool
* int
* float (floating-point number)
* string
* array
* object
* callable
* resource

PHP – динамически типизированный язык, что означает, что по умолчанию нет необходимости указывать тип переменной, так как он будет определён во время выполнения. Однако можно статически типизировать некоторые аспекты языка, используя декларации типов.

Полезные ссылки:

* [Типы данных](https://github.com/MaksimDzhangirov/PHP-cheatsheet/blob/master/Data-types.md)

### Переменные, константы

Переменные в PHP представлены знаком доллара с последующим именем переменной. Имя переменной чувствительно к регистру.

Имена переменных соответствуют тем же правилам, что и остальные наименования в PHP. Правильное имя переменной должно начинаться с буквы или символа подчёркивания и состоять из букв, цифр и символов подчёркивания в любом количестве.

Константа – это идентификатор (имя) для простого значения. Как следует из названия, это значение не может измениться в ходе выполнения скрипта. Константы чувствительны к регистру. По принятому соглашению, имена констант всегда пишутся в верхнем регистре.

Полезные ссылки:

* [Переменные](https://www.php.net/manual/ru/language.variables.php)
* [Константы](https://www.php.net/manual/ru/language.constants.php)

### Выражения, операторы

Выражения – это самые важные строительные элементы PHP. Почти всё, что вы пишете в PHP, является выражением. Самое простое и точное определение выражения — *все что угодно, имеющее значение*.

Оператором называется нечто, принимающее одно или более значений (или выражений), и вычисляющее новое значение (таким образом, вся конструкция может рассматриваться как выражение).

Операторы можно сгруппировать по количеству принимаемых ими значений. Унарные операторы принимают только одно значение, например, `!` (оператор логического отрицания) или `++` (инкремент). Бинарные операторы принимают два значения; это, например, знакомые всем арифметические операторы `+` (плюс) и `-` (минус), большинство поддерживаемых в PHP операторов входят именно в эту категорию. Ну и, наконец, есть всего один тернарный оператор, `? :`, принимающий три значения, обычно его так и называют – *тернарный оператор*.

Полезные ссылки:

* [Выражения](https://www.php.net/manual/ru/language.expressions.php)
* [Операторы](https://www.php.net/manual/ru/language.operators.php)

### Управляющие конструкции

Все скрипты в PHP представляют собой набор различных выражений, которые выполняются последовательно. Выражения можно объединять в группы выражений при помощи *операторных скобок* `{` и `}`. Группы выражений используются в основном вместе с управляющими конструкциями языка PHP.

Управляющие конструкции языка – это наборы служебных слов, позволяющие изменять ход выполнения скрипта. Все конструкции можно условно разделить на конструкции бинарного выбора, множественного выбора, повторения и включения.

Конструкции бинарного (двойственного) выбора позволяют в зависимости от условия выполнить либо первое, либо второе действие. В PHP эти конструкции представлены ключевыми словами `if`, `else`, `elseif` и `endif`.

Конструкция множественного выбора представляет собой компактную форму записи длинных цепочек условий вида `if...elseif...elseif......else`. В PHP такая конструкция носит название `switch`.

Конструкции повторения (организации циклов) предназначены для многократного выполнения одних и тех же выражений. К этим конструкциям относятся `while`, `do-while`, `for` и 
`foreach`.

Последняя группа конструкций – конструкции включения. Они предназначены для включения в текст скрипта каких-либо данных и кода, находящихся в другом файле. Всего существует четыре варианта: `include`, `include_once`, `require`, `require_once`.

Конструкции с приставкой `_once` отличаются от прочих тем, что гарантируют однократное включение файла в рамках всех задействованых файлов. `include_once` или `require_once` предварительно проверят предыдущие включения, и если файл уже был подключен – повторно подключать его не будут. Отличие между `include` и `require` заключено в поведении при отсутсвующем файле для подключения. Если `include` или `inclide_once` не находят указанный файл, то выдают предупреждение для пользователя. А вот `require` и `require_once` генерируют ошибку и прекращают дальнейшее выполнение скрипта.

Полезные ссылки:

* [Управляющие конструкции](https://www.php.net/manual/ru/language.control-structures.php)

### Функции

Функции представляют собой блок инструкций, которые многократно можно вызывать в различных частях программы. Функции позволяют разделять программуу на меньшие функциональные части.

Определение функции начинается с ключевого слова `function`, за которым следует имя функции. Имя функции должно начинаться с алфавитного символа или подчеркивания, за которыми может следовать любое количество алфавитно-цифровых символов или символов подчеркивания.

После имени функции в скобках идет перечисление параметров. Даже если параметров у функции нет, то просто идут пустые скобки. Затем в фигурных скобках идет тело функции, содержащее набор инструкций.

Полезные ссылки:

* [Функции](https://www.php.net/manual/ru/language.functions.php)

## Более сложные темы
### Классы и объекты

PHP включает полноценную объектную модель. Некоторые из её особенностей: видимость, абстрактные и ненаследуемые (`final`) классы и методы, а также магические методы, интерфейсы и клонирование.

PHP работает с объектами так же, как с ссылками или дескрипторами, это означает что каждая переменная содержит ссылку на объект, а не его копию.

Полезные ссылки:

* [Классы и объекты](https://www.php.net/manual/ru/language.oop5.php)

#### Статические методы и свойства

Объявление свойств и методов класса статическими позволяет обращаться к ним без создания экземпляра класса.

Пример статического метода и свойства.

```php
<?php

class Foo {
    // статическое свойство
    static public $aStaticNumber = 0;
    // статический метод
    public static function aStaticMethod() {
        // ...
    }
}
?>
```

Поскольку доступ к статическому элементу осуществляется через класс, а не экземпляр объекта, вам не нужна переменная, которая ссылается на объект. Вместо этого используется имя класса, после которого указывается два двоеточия "::".

```php
<?php

Foo::$aStaticNumber;
Foo::aStaticMethod();

?>
```

Статические элементы имеют ряд полезных особенностей:

1. они доступны из любой точки сценария. Это означает, что можно вызывать функции, не передавая экземпляр класса от одного объекта другому или сохраняя экземпляр объекта в глобальной переменной.
2. статическое свойство доступно каждому экземпляру объекта этого класса, поэтому можно определить значения, которые должны быть доступны всем объектам данного типа.
3. позволяют не создавать экземпляр объекта ради вызова статической функции.

Полезные ссылки:

* [Ключевое слово static](https://www.php.net/manual/ru/language.oop5.static.php)

#### Абстрактные классы

Классы, определенные как абстрактные, не могут быть созданы, и любой класс, который содержит по крайней мере один абстрактный метод, должен быть определен как абстрактный. Абстрактный метод не может иметь реализацию в абстрактном классе. Он объявляется, как обычный метод, но объявление заканчивается точкой с запятой, а не телом метода.

```php
<?php

abstract class AbstractClass
{
   /* Данный метод должен быть определён в дочернем классе */
    abstract protected function getValue();
    abstract protected function prefixValue($prefix);

   /* Общий метод */
    public function printOut() {
        print $this->getValue() . "\n";
    }
}

?>
```

Полезные ссылки:

* [Абстрактные классы](https://www.php.net/manual/ru/language.oop5.abstract.php)

#### Интерфейсы

Интерфейсы объектов позволяют создавать код, который указывает, какие методы должен реализовать класс, без необходимости определять, как эти методы обрабатываются.

Интерфейсы объявляются так же, как и обычные классы, но с использованием ключевого слова `interface` вместо `class`. Тела методов интерфейсов должны быть пустыми.

Для реализации интерфейса используется оператор `implements`. Класс должен реализовать все методы, описанные в интерфейсе, иначе произойдет фатальная ошибка. При желании классы могут реализовывать более одного интерфейса, разделяя каждый интерфейс запятой.

```php
<?php

// Объявим интерфейс 'iTemplate'
interface iTemplate
{
    public function setVariable($name, $var);
    public function getHtml($template);
}

// Реализация интерфейса
// Это будет работать
class Template implements iTemplate
{
    private $vars = array();
  
    public function setVariable($name, $var)
    {
        $this->vars[$name] = $var;
    }
  
    public function getHtml($template)
    {
        foreach($this->vars as $name => $value) {
            $template = str_replace('{' . $name . '}', $value, $template);
        }
 
        return $template;
    }
}
?>
```

Все методы, определенные в интерфейсы должны быть объявлены как `public`.

Интерфейс может содержать публичные методы (простые и статические), а также константы. Интерфейс НЕ может содержать любые свойства, непубличные методы и константы, методы с реализацией.

В РНР не поддерживается множественное наследование. Однако эту проблему можно решить с помощью интерфейсов. Другими словами, для каждого класса в РНР может существовать только один родительский класс. Тем не менее в каждом классе можно реализовать произвольное количество интерфейсов. При этом данный класс будет соответствовать типам всех тех интерфейсов, которые в нем реализованы.

Полезные ссылки:

* [Интерфейсы объектов](https://www.php.net/manual/ru/language.oop5.interfaces.php)

#### Трейты

Трейт – это механизм обеспечения повторного использования кода в языках с поддержкой только одиночного наследования, таких как PHP. Трейт предназначен для уменьшения некоторых ограничений одиночного наследования, позволяя разработчику повторно использовать наборы методов свободно, в нескольких независимых классах и реализованных с использованием разных архитектур построения классов. Любое свойство (или метод), определенное в трейте, становится частью того класса, в который этот трейт включен. При этом трейт изменяет структуру этого класса, но не меняет его тип.

**Пример использования трейта**

```php
<?php
trait ezcReflectionReturnInfo {
    function getReturnType() { /*1*/ }
    function getReturnDescription() { /*2*/ }
}

class ezcReflectionMethod extends ReflectionMethod {
    use ezcReflectionReturnInfo;
    /* ... */
}

class ezcReflectionFunction extends ReflectionFunction {
    use ezcReflectionReturnInfo;
    /* ... */
}
?>
```

##### Особенности использования трейтов
###### Использование нескольких трейтов

В класс можно включить несколько трейтов. Для этого их нужно перечислить через запятую после ключевого слова `use`.

```php
<?php
trait Hello {
    public function sayHello() {
        echo 'Hello ';
    }
}

trait World {
    public function sayWorld() {
        echo 'World';
    }
}

class MyHelloWorld {
    use Hello, World;
    public function sayExclamationMark() {
        echo '!';
    }
}

$o = new MyHelloWorld();
$o->sayHello();
$o->sayWorld();
$o->sayExclamationMark();
?>
```

###### Совместное использование трейтов и интерфейсов

Как было сказано выше, трейты не позволяют изменить тип класса, в который были включены. Поэтому, если трейт используется сразу в нескольких классах, у вас не будет общего типа, который можно было бы указать в уточнениях для сигнатур методов. К счастью, трейты можно успешно использовать вместе с интерфейсами. Мы можем определить интерфейс с методами, которые затем реализуем в трейте, а затем указать, что в нужном нам классе реализуются методы этого интерфейса.

###### Устранение конфликтов имен с помощью ключевого слова `insteadof`. Псевдонимы для переопределенных методов трейта

Если два трейта вставляют метод с одним и тем же именем, это приводит к фатальной ошибке в случае, если конфликт явно не разрешен.

Для разрешения конфликтов именования между трейтами, используемыми в одном и том же классе, необходимо использовать оператор `insteadof` для того, чтобы точно выбрать один из конфликтующих методов.

Так как предыдущий оператор позволяет только исключать методы, оператор `as` может быть использован для включения одного из конфликтующих методов под другим именем. Оператор `as` не переименовывает метод и не влияет на какой-либо другой метод.

```php
<?php
trait A {
    public function smallTalk() {
        echo 'a';
    }
    public function bigTalk() {
        echo 'A';
    }
}

trait B {
    public function smallTalk() {
        echo 'b';
    }
    public function bigTalk() {
        echo 'B';
    }
}

class Talker {
    use A, B {
        B::smallTalk insteadof A;
        A::bigTalk insteadof B;
    }
}

class Aliased_Talker {
    use A, B {
        B::smallTalk insteadof A;
        A::bigTalk insteadof B;
        B::bigTalk as talk;
    }
}
?>
```

###### Использование статических методов в трейте

На статические переменные можно ссылаться внутри методов трейта, но нельзя определить статические переменные в самом трейте. Тем не менее, трейт может описывать статические методы для демонстрации класса.

```php
<?php
trait Counter {
    public function inc() {
        static $c = 0;
        $c = $c + 1;
        echo "$c\n";
    }
}

class C1 {
    use Counter;
}

class C2 {
    use Counter;
}

$o = new C1(); $o->inc(); // echo 1
$p = new C2(); $p->inc(); // echo 1
?>
```

###### Определение абстрактных методов в трейтах

В трейтах можно объявлять абстрактные методы точно так же, как и в обычных классах. При использовании такого трейта в классе в нем должны быть реализованы все объявленные в трейте абстрактные методы.

```php
<?php
trait Hello {
    public function sayHelloWorld() {
        echo 'Hello'.$this->getWorld();
    }
    abstract public function getWorld();
}

class MyHelloWorld {
    private $world;
    use Hello;
    public function getWorld() {
        return $this->world;
    }
    public function setWorld($val) {
        $this->world = $val;
    }
}
?>
```

###### Изменение прав доступа к методам трейта

Используя синтаксис оператора `as` можно также настроить видимость метода в использующем трейт классе.

```php
<?php
trait HelloWorld {
    public function sayHello() {
        echo 'Hello World!';
    }
}

// Изменение видимости класса sayHello
class MyClass1 {
    use HelloWorld { sayHello as protected; }
}

// Создание псевдонима метода с измененной видимостью
// видимость sayHello не изменилась
class MyClass2 {
    use HelloWorld { sayHello as private myPrivateHello; }
}
?>
```

###### Трейты, состоящие из трейтов

Аналогично тому, как классы могут использовать трейты, также и трейты могут использовать другие трейты.

```php
<?php
trait Hello {
    public function sayHello() {
        echo 'Hello ';
    }
}

trait World {
    public function sayWorld() {
        echo 'World!';
    }
}

trait HelloWorld {
    use Hello, World;
}

class MyHelloWorld {
    use HelloWorld;
}

$o = new MyHelloWorld();
$o->sayHello();
$o->sayWorld();
?>
```

###### Свойства

Трейты могут также определять свойства.

```php
<?php
trait PropertiesTrait {
    public $x = 1;
}

class PropertiesExample {
    use PropertiesTrait;
}

$example = new PropertiesExample;
$example->x;
?>
```

Полезные ссылки:

* [Трейты](https://www.php.net/manual/ru/language.oop5.traits.php)

#### Позднее статическое связывание

Позднее статическое связывание может быть использовано для того, чтобы получить ссылку на вызываемый класс в контексте статического наследования. "Позднее связывание" отражает тот факт, что обращения через `static::` не будут вычисляться по отношению к классу, в котором вызываемый метод определен, а будут вычисляться на основе информации в ходе исполнения.

**Использование static::**

```php
<?php
class A {
    public static function who() {
        echo __CLASS__;
    }
    public static function test() {
        static::who(); // Здесь действует позднее статическое связывание
    }
}

class B extends A {
    public static function who() {
        echo __CLASS__;
    }
}

B::test();
?>
```

Позднее статическое связывание может использоваться, чтобы избежать дублирования кода из родительсикх классов в дочерние.

```php
abstract class DomainObject 
{
  public static function create () 
  {
    return new static ();
  }
class User extends DomainObject () 
{
}
class Document extends DomainObject () 
{
}
print_r(Document::create());
```

Ключевое слово `static` можно использовать не только для создания объектов. Так же, как и `self` и `parent`, его можно использовать как идентификатор для вызова статических методов даже из нестатического контекста.

```php
abstract class DomainObject
{
    private $group;
    public function __construct()
    {
        $this->group = static::getGroup();
    }
    public static function create(): DomainObject
    {
        return new static();
    }
    public static function getGroup(): string
    {
        return "default";
    }
}
class User extends DomainObject
{
}
class Document extends DomainObject
{
    public static function getGroup(): string
    {
        return "document";
    }
}
class SpreadSheet extends Document
{
}

print_r(User::create());
print_r(SpreadSheet::create());
```

Полезные ссылки:

* [Позднее статическое связывание](https://www.php.net/manual/ru/language.oop5.late-static-bindings.php)

#### Магические методы

Магические методы – это специальные методы, которые переопределяют действие PHP по умолчанию, когда над объектом выполняются определённые действия.

Полезные ссылки:

* [Магические методы](https://www.php.net/manual/ru/language.oop5.magic.php)

#### Наследование vs Композиция vs Агрегация

Наследование (англ. inheritance) — концепция объектно-ориентированного программирования, согласно которой абстрактный тип данных может наследовать данные и функциональность некоторого существующего типа, способствуя повторному использованию компонентов программного обеспечения.

Агрегирование (англ. object aggregation, object composition), или, как его называли ранее, делегирование, в объектно-ориентированном программировании — методика создания нового класса из уже существующих классов путём их включения. Об агрегировании также часто говорят как об «отношении принадлежности» по принципу «у машины есть корпус, колёса и двигатель».

Агрегация (агрегирование по ссылке) — отношение «часть-целое» между двумя равноправными объектами, когда один объект (контейнер) имеет ссылку на другой объект. Оба объекта могут существовать независимо: если контейнер будет уничтожен, то его содержимое — нет.

Композиция (агрегирование по значению) — более строгий вариант агрегирования, когда включаемый объект может существовать только как часть контейнера. Если контейнер будет уничтожен, то и включённый объект тоже будет уничтожен.

Полезные ссылки:

* [Наследование](https://ru.wikipedia.org/wiki/%D0%9D%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5))
* [Агрегирование](https://ru.wikipedia.org/wiki/%D0%90%D0%B3%D1%80%D0%B5%D0%B3%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5))
* [Наследование vs Композиция vs Агрегация](https://github.com/MaksimDzhangirov/PHP-cheatsheet/blob/master/inheritanceVsCompositionVsAggregation.md)

### Пространства имён

Пространства имён в широком смысле – это один из способов инкапсуляции элементов.

В PHP пространства имён используются для решения двух проблем, с которыми сталкиваются авторы библиотек и приложений при создании повторно используемых элементов кода, таких как классы и функции:

1. Конфликт имён между вашим кодом и внутренними классами/функциями/константами PHP или сторонними.
2. Возможность создавать псевдонимы (или сокращения) для Ну_Очень_Длинных_Имён, чтобы облегчить первую проблему и улучшить читаемость исходного кода.

Полезные ссылки:

* [Пространства имён](https://www.php.net/manual/ru/language.namespaces.php)

### Ошибки и исключения

PHP сообщает об ошибках в ответ на некоторые внутренние ошибочные обстоятельства. Они могут быть использованы для уведомления о разных состояниях, а также могут выводиться на экран и записываться в логи по желанию.

Каждая ошибка, генерируемая PHP, обязательно содержит информацию о своём типе. [В этом списке](https://www.php.net/manual/ru/errorfunc.constants.php) перечислены все типы ошибок, а также описания их поведений и провоцирующие их причины.

В PHP реализована модель исключений, аналогичная тем, что используются в других языках программирования. Исключение в PHP может быть выброшено (`throw`) и поймано (`catch`). Код может быть заключён в блок `try`, чтобы облегчить обработку потенциальных исключений. У каждого блока `try` должен быть как минимум один соответствующий блок `catch` или `finally`.

Если выброшено исключение, а в текущей области видимости функции нет блока `catch`, исключение будет *подниматься* по стеку вызовов к вызывающей функции, пока не найдёт подходящий блок `catch`. Все блоки `finally`, которые встретятся на этом пути, будут выполнены. Если стек вызовов разворачивается до глобальной области видимости, не встречая подходящего блока `catch`, программа завершается с неисправимой ошибкой, если не был установлен глобальный обработчик исключений.

Полезные ссылки:

* [Ошибки](https://www.php.net/manual/ru/language.errors.php)
* [Исключения](https://www.php.net/manual/ru/language.exceptions.php)

### Генераторы

Генераторы предоставляют лёгкий способ реализации простых итераторов без использования дополнительных ресурсов или сложностей, связанных с реализацией класса, реализующего интерфейс `Iterator`.

Генератор позволяет вам писать код, использующий `foreach` для перебора набора данных без необходимости создания массива в памяти, что может привести к превышению лимита памяти, либо потребует довольно много времени для его создания. Вместо этого, вы можете написать функцию-генератор, которая, по сути, является обычной функцией, за исключением того, что вместо возврата единственного значения, генератор может возвращать (`yield`) столько раз, сколько необходимо для генерации значений, позволяющих перебрать исходный набор данных.

Полезные ссылки:

* [Генераторы](https://www.php.net/manual/ru/language.generators.php)

### SPL – Стандартная библиотека PHP

Стандартная библиотека PHP (SPL) – это набор интерфейсов и классов, предназначенных для решения стандартных задач.

SPL предоставляет ряд стандартных структур данных, итераторов для оббегания объектов, интерфейсов, стандартных исключений, некоторое количество классов для работы с файлами и предоставляет ряд функций, например `spl_autoload_register()`.

Полезные ссылки:

* [SPL – Стандартная библиотека PHP](https://www.php.net/manual/ru/book.spl.php)

#### Структуры данных

SPL предоставляет набор стандартных структур данных. Они сгруппированы здесь по своей базовой реализации, которая обычно определяет их общую область применения.

Полезные ссылки:

* [Структуры данных](https://www.php.net/manual/ru/spl.datastructures.php)
* [Двусвязные списки](https://www.php.net/manual/ru/class.spldoublylinkedlist.php)
* [Стек](https://www.php.net/manual/ru/class.splstack.php)
* [Очередь](https://www.php.net/manual/ru/class.splqueue.php)
* [Куча](https://www.php.net/manual/ru/class.splheap.php)
* [Очередь с приоритетом](https://www.php.net/manual/ru/class.splpriorityqueue.php)
* [Массив фиксированной длины](https://www.php.net/manual/ru/class.splfixedarray.php)
* [Отображение объектов в данные](https://www.php.net/manual/ru/class.splobjectstorage.php)

## Composer

Composer – это пакетный менеджер уровня приложений для языка программирования PHP, который предоставляет средства по управлению зависимостями в PHP-приложении. Composer разработали и продолжают поддерживать два программиста Nils Adermann и Jordi Boggiano. Они начали разрабатывать Composer в апреле 2011, а первый релиз состоялся 1 марта 2012. Идея создания пакетных менеджеров уровня приложений не нова и его авторы вдохновлялись уже существовавшими на тот момент времени `npm` для `Node.js` и `bundler` для `Ruby`.

Composer работает через интерфейс командной строки и устанавливает зависимости (например библиотеки) для приложения. Он также позволяет пользователям устанавливать PHP-приложения, которые доступны на [packagist.org](https://packagist.org/), который является его основным репозиторием, где содержатся все доступные пакеты.

### require, install, update

#### require

Команда `require` добавляет новые пакеты в файл `composer.json` из текущего каталога. Если файла не существует, он будет создан на лету.
После добавления/изменения зависимостей, они будут установлены или обновлены.
Если вы не хотите выбирать зависимости в интерактивном режиме, вы можете передать их команде.

```shell
php composer.phar require "vendor/package:2.*" vendor/package2:dev-master
```

Если вы не укажете пакет, Composer предложит вам выполнить поиск пакета и, получив результаты, предоставит список совпадений для затребованного.

#### install

Команда `install` считывает файл `composer.json` из текущего каталога, разрешает зависимости и устанавливает их в `vendor`.

```shell
php composer.phar install
```

Если в текущем каталоге есть файл `composer.lock`, он будет использовать конкретные версии оттуда, а не разрешать их. Это гарантирует, что все, кто использует библиотеку, получат одинаковые версии зависимостей.

Если файла `composer.lock` нет, Composer создаст его после разрешения зависимостей.

#### update

Чтобы получить последние версии зависимостей и обновить файл `composer.lock`, вы должны использовать команду `update`. Эта команда также называется `upgrade`, поскольку она делает то же самое, что и `upgrade`, если сравнивать с `apt-get` или подобными менеджерами пакетов.

```shell
php composer.phar update
```

Это разрешит все зависимости проекта и запишет конкретные версии в `composer.lock`.

Если вы хотите обновить только несколько пакетов, а не все, вы можете перечислить их следующим образом:

```shell
php composer.phar update vendor/package vendor/package2
```

Вы также можете использовать символ звёздочки для одновременного обновления нескольких пакетов:

```shell
php composer.phar update "vendor/*"
```

Если вы хотите понизить версию пакета до определенной версии, не изменяя ваш composer.json, вы можете использовать `--with` и указать ограничение версии:

```shell
php composer.phar update --with vendor/package:2.0.1
```

Обратите внимание, что при использовании показанной выше команды, будут обновлены все пакеты. Если вы хотите обновить только пакеты, для которых вы указали ограничения с помощью `--with`, вы можете опустить `--with` и вместо этого использовать:

```shell
php composer.phar update vendor/package:2.0.1 vendor/package2:3.0.*
```

Для пакетов, которые также находятся в вашем `composer.json`, ограничение, вводимое Вами, должно быть подмножеством существующих ограничений.

Полезные ссылки:

* [require](https://getcomposer.org/doc/03-cli.md#require-r)
* [install](https://getcomposer.org/doc/03-cli.md#install-i)
* [update](https://getcomposer.org/doc/03-cli.md#update-u-upgrade)

### Система управления пакетами

Система управления пакетами – набор программного обеспечения, позволяющего управлять процессом установки, удаления, настройки и обновления различных компонентов программного обеспечения.

Использование на практике системы управления пакетами Composer позволяет автоматизировать не только процесс установки и обновления пакетов, но и дает возможность использовать одни и те же версии пакетов среди всех разработчиков.

Полезные ссылки:

* [Система управления пакетами](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D0%B0%D0%BC%D0%B8)

### Packagist

Packagist – это хостинг PHP-пакетов. Это дефолтный хостинг Composer. Каждый месяц Composer используется для загрузки более 2 миллиардов пакетов. Packagist представляет собой один из крупнейших хостинговых сервисов в экосистеме PHP.

Полезные ссылки:

* [Packagist](https://packagist.org/)

### Автозагрузка

Благодаря появлению такого инструмента как Composer, появился универсальный инструмент автозагрузки. Теперь, чтобы написать свою библиотеку или приложение, нет необходимости писать свой автозагрузчик классов, и поэтому можно сосредоточиться на написании кода вашего приложения. Более того, появился универсальный инструмент подключение сторонних библиотек, если в этом есть необходимость.

Ранее написание автозагрузчика классов осуществлялось с помощью PHP функции `spl_autoload_register`, и каждый сам организовывал структуру приложения в соответствии с придуманным им правилами. Для того, чтобы все разработчики придерживались предопределенных правил и не придумывали свои, сообщество PHP разработчиков написали рекомендации (стандарты) PSR-0 и PSR-4, которые позволят всем PHP программистам организовывать структуру таким образом, чтобы их приложение было проще понимать другим. В настоящий момент следует организовывать автозагрузку в соответствии с PSR-4, поскольку это более актуальный и рекомендуемый на данный момент способ организации структуры.

Полезные ссылки:

* [Автоматическая загрузка классов](https://www.php.net/manual/ru/language.oop5.autoload.php)
* [Автозагрузка классов с Composer в PHP](https://webformyself.com/avtozagruzka-klassov-s-composer-v-php/)

## Работа с базами данных в PHP

Базы данных широко применяются для структурирования и хранения информации. Таким образом, на практике базы данных применяют:

* для сохранения пользовательских данных, полученных с помощью форм;
* для проверки, существует ли конкретный аккаунт в системе, какие у него права доступа;
* для организации поиска по страницам сайта;
* для хранения комментариев;
* для хранения всевозможного контента (статей, изображений, медиафайлов) и многих других данных.

Но прежде, чем выполнить какую-нибудь операцию с записями, находящимися в БД, нужно сначала к этой БД подключиться.

Традиционно, язык программирования PHP поддерживает работу с такой базой данных, как MySQL. Для работы с базой данных MySQL в PHP встроены специальные функции, то есть необходимые возможности предусмотрены заранее. Эти функции позволяют:

* выполнять запросы и получать результаты;
* обрабатывать ошибки;
* читать и записывать данные;

При подключении к MySQL соответствующий сценарий исполняет запрос и показывает результат запроса. Но самое главное заключается в том, что для работы с СУБД MySQL разработчику не придется ничего специально устанавливать, так как все нужное будет сразу доступно и включено в стандартный пакет PHP.

### PDO

Модуль `PHP Data Objects` (PDO) определяет простой и согласованный интерфейс для доступа к базам данных в PHP. Каждый драйвер базы данных, в котором реализован этот интерфейс, может представить специфичную для базы данных функциональность в виде стандартных функций модуля. Но надо заметить, что сам по себе модуль PDO не позволяет манипулировать доступом к базе данных. Чтобы воспользоваться возможностями PDO, необходимо использовать соответствующий конкретной базе данных PDO драйвер.

PDO обеспечивает абстракцию *доступу к данным*, это значит, что вне зависимости от того, какая конкретная база данных используется, вы можете пользоваться одними и теми же функциями для выполнения запросов и выборки данных. PDO *не* абстрагирует саму *базу данных*, этот модуль не переписывает SQL-запросы и не эмулирует отсутствующий в СУБД функционал. Если нужно именно это, необходимо воспользоваться полноценной абстракцией базы данных.

Модуль PDO внедрён в PHP.

Полезные ссылки:

* [PDO](https://www.php.net/manual/ru/book.pdo.php)

### ORM

ORM (Object-Relation Mapping, объектно-реляционное отображение) – общее название для библиотек, позволяющих автоматически связать базу данных с кодом. Они стараются скрыть существование базы данных настолько, насколько это возможно. Взамен, программисту дают возможность оперировать данными в базе через специальный интерфейс. Вместо построения SQL-запросов, программист вызывает простые методы, а всю остальную работу берёт на себя ORM.

Полезные ссылки:

* [ORM](https://ru.wikipedia.org/wiki/ORM)
* [Список ORM-библиотек](https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_ORM-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA#PHP)

#### Doctrine

Doctrine – ORM для PHP 7.1+, который базируется на слое абстракции доступа к БД (DBAL). Одной из ключевых возможностей Doctrine является запись запросов к БД на собственном объектно-ориентированном диалекте SQL, называемом DQL (Doctrine Query Language) и базирующемся на идеях HQL (Hibernate Query Language).

Полезные ссылки:

* [Doctrine](https://www.doctrine-project.org/)
* [Doctrine](https://ru.wikipedia.org/wiki/Doctrine)

## Отладка

Отладка – этап разработки компьютерной программы, на котором обнаруживают, локализуют и устраняют ошибки. Чтобы понять, где возникла ошибка, приходится:

* узнавать текущие значения переменных;
* выяснять, по какому пути выполнялась программа.

Существуют две взаимодополняющие технологии отладки:

* Использование отладчиков – программ, которые включают в себя пользовательский интерфейс для пошагового выполнения программы: оператор за оператором, функция за функцией, с остановками на некоторых строках исходного кода или при достижении определённого условия.

* Вывод текущего состояния программы с помощью расположенных в критических точках программы операторов вывода – на экран, принтер или в файл. Вывод отладочных сведений в файл называется логированием.

### xDebug

xDebug – средство профилирования и отладки PHP-скриптов. XDebug поставляется как расширение для PHP и работает по протоколу DBGp.

Полезные ссылки:

* [xDebug](https://xdebug.org/)
* [Xdebug](https://ru.wikipedia.org/wiki/Xdebug)

### Zend Debugger

PHP расширение, которое необходимо установить на ваш веб-сервер для оптимальной удаленной отладки и профилирования с помощью Zend Studio.

Полезные ссылки:

* [Zend Debugger](https://www.zend.com/downloads/zend-studio-web-debugger)

## Качество кода

Качество кода — это измерение того, насколько высока или низка ценность определенного набора кода, программы или программного обеспечения. Как правило, код является высококачественным, если строки кода легко интерпретируются и если разработчик задокументировал код. Качественный код часто отвечает следующим параметрам:

* Функциональный
* Последовательный
* Его легко понять
* Удовлетворяет потребностям клиентов
* Тестируемый
* Поддерживает многоразовое использование
* В нём отсутствуют ошибки и недочеты
* Безопасный
* Хорошо документированный

### PSR-12

Cпецификация PSR-12 расширяет и заменяет руководство по стилю кодирования PSR-2 и требует соблюдения PSR-1, основного стандарта кодирования.

Как и PSR-2, цель данной рекомендации, уменьшить когнитивные разногласия при просмотре кода разных авторов. Это достигается путем перечисления общего набора правил и ожиданий о том, как форматировать код на PHP. Этот PSR стремится обеспечить набор способов, который может реализовать механизмы стиля кодирования. Проекты могут заявить о соблюдении, а разработчики могут легко устанавливать связь между различными проектами. Когда разные авторы работают над несколькими проектами, это помогает достичь одного набора стиля кодирования, который будет использоваться во всех этих проектах. Таким образом, преимущество этого руководства заключается не в самих правилах, а в совместном использовании этих правил.

PSR-2 был принят в 2012 году, и с тех пор в PHP был внесен ряд изменений, которые повлияли на рекомендации по стилю кодирования. В то время как PSR-2 полно отражает функциональность PHP, существовавшую на момент написания, новую функциональность можно интерпретировать по-разному. Таким образом, этот PSR стремится прояснить содержание PSR-2 в более современном контексте с доступными новыми функциональными возможностями и внести поправки в PSR-2.

Полезные ссылки:

* [PSR-12](https://www.php-fig.org/psr/psr-12/)

### CodeSniffer

PHP CodeSniffer состоит из двух скриптов; главный `phpcs` размечает PHP, JavaScript, CSS файлы для обнаружения нарушений определенных стандартов кода. Второй скрипт `phpcbf` автоматически исправляет ошибки в коде. CodeSniffer — это полезный инструмент разработчика, гарантирующий чистоту и последовательность кода.

Полезные ссылки:

* [CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)

### Psalm

Бесплатный с открытым исходным кодом инструмент статического анализа PHP приложений на наличие ошибок. Кроме того в его состав входит иснтрумент под названием Psalter, который может помочь вам исправить найденные ошибки.

Полезные ссылки:

* [Psalm](https://psalm.dev/)

### Phan

Phan — статический анализатор для PHP. Phan предпочитает избегать ложных срабатываний и пытается доказать неправоту, а не правильность.
Может требовать много памяти на больших проектах.

Полезные ссылки:

* [Phan](https://github.com/phan/phan)

### PHPStan

PHPStan фокусируется на поиске ошибок в вашем коде, фактически не запуская его. Он отлавливает целые классы ошибок ещё до того, как вы напишете тесты для кода. Он приближает PHP к компилируемым языкам в том смысле, что правильность каждой строки кода можно проверить до того, как вы запустите эту строку.

* можно анализировать не всю кодовую базу, а только часть;
* существует возможность писать плагины;
* настройки в формате neon;
* постепенно нарастающая сложность анализа.

Полезные ссылки:

* [PHPStan](https://phpstan.org/)

## Кэширование

Кэширование – это процесс хранения часто используемых данных во временном хранилище, называемом кешем. Цель кэширования — повысить производительность приложений и системы за счет сокращения времени, необходимого для доступа к данным. При запросе данных, хранящихся в кеше, система может извлечь данные из кеша вместо того, чтобы извлекать их из исходного источника, что может быть медленнее.

### PSR-6 и PSR-16

Цель PSR-6 – позволить разработчикам создавать библиотеки с поддержкой кэширования, которые можно интегрировать в существующие платформы и системы без необходимости специальной разработки. PSR-16 более простой подход направленный на создание стандартизированного оптимизированного интерфейса для часто встречающихся случаев. Он не зависит от PSR-6, но был разработан для максимально простой совместимости с PSR-6.

Полезные ссылки:

* [PSR-6](https://www.php-fig.org/psr/psr-6/)
* [PSR-16](https://www.php-fig.org/psr/psr-16/)

### APCu

APCu – это хранилище «ключ-значение» в памяти для PHP. Ключи являются строками (string), а значения могут быть любыми переменными PHP. APCu поддерживает только кеширование переменных в пользовательском пространстве.

Полезные ссылки:

* [APCu](https://www.php.net/manual/ru/book.apcu.php)

### Файловая система

Когда нет возможности установить APCu или Redis, то кеш можно хранить в файловой системе. Считать информацию из файла и выполнить десериализацию часто бывает намного быстрее, чем выполнить громоздкий SELECT запрос с несколькими джойнами.

Полезные ссылки:

* [Filesystem Cache Adapter](https://symfony.com/doc/current/components/cache/adapters/filesystem_adapter.html)

## Тестирование

Тестирование — процесс исследования, испытания программного продукта, имеющий своей целью проверку соответствия между реальным поведением программы и её ожидаемым поведением на конечном наборе тестов, выбранных определённым образом.

### PHPUnit

PHPUnit – фреймворк для unit тестирования при разработке ПО на PHP. Является представителем семейства фреймворков XUnit на основе пакета SUnit, созданного Кентом Беком. PHPUnit разработан Себастьяном Бергманом.

Основная идея PHPUnit – чем раньше вы обнаружите ошибки в коде, тем быстрее вы сможете их исправить. Как и все фреймворки для unit тестирования PHPUnit использует assertions (утверждения) для проверки, что конкретный компонент ведёт себя как и ожидалось.

Полезные ссылки:

* [PHPUnit](https://phpunit.de/)

### Codeception

Codeception — это популярный фреймворк для тестирования веб-приложений. Он написан поверх PHPUnit и позволяет более элегантно писать тесты используя методологию BDD. BDD (behaviour-driven development) — это разработка, основанная на описании поведения, что облегчает написание и чтение кода тестов. Поддерживает приемочные, функциональные и unit тесты.

Полезные ссылки:

* [Codeception](https://codeception.com/)

### Behat

Behat — это фреймворк для тестирования, использующий методологию BDD. Behat был создан Константином Кудряшовым, а его разработка ведется на GitHub. Behat предназначен для облегчения общения между разработчиками, клиентами и другими заинтересованными сторонами в процессе разработки программного обеспечения.

Полезные ссылки:

* [Behat](https://behat.org/)

## Веб-фреймворки

Веб-фреймворк – [фреймворк](https://ru.wikipedia.org/wiki/%D0%A4%D1%80%D0%B5%D0%B9%D0%BC%D0%B2%D0%BE%D1%80%D0%BA), предназначенный для создания динамических веб-сайтов, сетевых приложений, сервисов или ресурсов. Он упрощает разработку и избавляет от необходимости написания рутинного кода. Многие фреймворки упрощают доступ к базам данных, разработку интерфейса, и также уменьшают дублирование кода. Большая часть фреймворков веб-приложений реализует шаблон проектирования [Model-View-Controller](https://ru.wikipedia.org/wiki/Model-View-Controller) (MVC). Однако, также могут использоваться и другие шаблоны, например, Model-View-Presenter или Model-View-ViewModel.

### Symfony

Symfony – фреймворк с открытым исходным кодом, написанный на PHP.

Symfony обеспечивает быструю разработку и управление веб-приложениями, позволяет легко решать рутинные задачи веб-программиста. Работает только с PHP 5 и выше. Symfony бесплатен и публикуется под лицензией MIT. Проект спонсируется французской компанией SensioLabs.

Полезные ссылки:

* [Symfony site](https://symfony.com/)

### Laravel

Laravel – бесплатный веб-фреймворк с открытым кодом, предназначенный для разработки с использованием архитектурной модели MVC. Он выпущен под лицензией MIT. Исходный код проекта размещается на GitHub. Laravel был создан Taylor Otwell как более функциональная альтернатива CodeIgniter, который не предусматривал различные дополнительные функции.

Полезные ссылки:

* [Laravel site](https://laravel.com/)

### Yii

Yii – объектно-ориентированный компонентный фреймворк, реализующий парадигму MVC. Фреймворк отлично документирован: документация есть ко всему и на нескольких языках (русский, украинский, английский, испанский и другие). Аналогично другим фреймворкам в Yii используются паттерны Dependency Injection (DI) и Service Locator. Yii выпущен под модифицированной лицензией BSD. Это означает, что можно использовать его бесплатно для разработки как открытых, так и проприетарных веб-приложений.

Полезные ссылки:

* [Полное руководство по Yii 2.0](https://www.yiiframework.com/doc/guide/2.0/ru)

### CakePHP

CakePHP — это фреймворк для создания веб-приложений, написанный на языке PHP и построенный на принципах открытого ПО. CakePHP реализует паттерн MVC. Публикуется под лицензией MIT.

Изначально создавался как клон популярного Ruby on Rails, и многие идеи были заимствованы именно оттуда:

1. Своя файловая структура
2. Поддержка множества плагинов
3. Абстракция данных
4. Поддержка множества СУБД (PostgreSQL, MySQL, SQLite)

Полезные ссылки:

* [CakePHP site](https://cakephp.org/)

## Логирование

Лог (log) — это хронологическая запись наиболее значимой информации о работе системы. Подобная фиксация событий дает представление и том, что происходило в системе, в какой именно момент, какой пользователь спровоцировал то или иное событие, какие ошибки возникли и т. д.

Логирование — это процесс формирования логов, а именно: фиксация и структурирование информации о работе системы в отдельные лог-файлы с возможностью быстрого доступа к ним в случае необходимости. Файлы содержат отчет обо всем, что происходило с системой: какие действия совершали конкретные пользователи, когда это происходило, как система реагировала на события и т.д.

### PSR-3

В этом документе описывается общий интерфейс для библиотеки логирования.

Главная цель позволить библиотекам получать обьект Psr\Log\LoggerInterface и записывать в него логи простым и универсальным способом. Фреймворки и CMS могут расширить интерфейс для своих собственных целей, но должны оставаться совместимыми с этим документом.

Полезные ссылки:

* [PSR-3](https://www.php-fig.org/psr/psr-3/)

### Monolog

Monolog — одна из популярных PHP-библиотек логирования, позволяющая передавать логи в файлы, сокеты, почтовые ящики, базы данных и различные веб-сервисы. Полный список обработчиков моно найти на GitHub. Эта библиотека реализует интерфейс PSR-3, чтобы обеспечить максимальную совместимость. Доступен из коробки в Symfony и Laravel и устанавливается с помощью плагинов в Yii и CakePHP.

Полезные ссылки:

* [Страница на GitHub](https://github.com/Seldaek/monolog)

### Sentry

Sentry — это ориентированная на разработчиков платформа для отслеживания ошибок и мониторинга производительности, которая помогает разработчикам понимать, что действительно важно, быстрее решать проблемы и постоянно узнавать что-то новое о своих приложениях. Поддерживает множество языков в том числе и PHP. Интеграция с Symfony и Laravel разрабатывается и поддерживается официальной командой Sentry, для Yii и CakePHP доступны плагины от членов сообщества Sentry.

Полезные ссылки:

* [Sentry site](https://sentry.io/welcome/)
* [Страница на GitHub](https://github.com/getsentry/sentry)
* [Sentry's PHP SDK](https://docs.sentry.io/platforms/php/)

## Профилирование

Профилирование — это сбор характеристик программы во время ее выполнения. При профилировании замеряется время выполнения и количество вызовов отдельных функций и строк в коде программы. При помощи этого инструмента программист может найти наиболее медленные участки кода и провести их оптимизацию. Инструмент, используемый для анализа работы, называют профилировщиком или профайлером.

### XHProf

XHProf — PHP-расширение от Facebook. Это иерархический профайлер, который позволяет собирать такую статистику как время выполнения каждой функции, использование памяти, время ожидания, количество вызовов и многое другое. Это расширение доступно из репозитория PECL: [http://pecl.php.net/package/xhprof](http://pecl.php.net/package/xhprof).

Полезные ссылки:

* [XHProf site](https://www.php.net/manual/ru/book.xhprof.php)

### Blackfire

Blackfire Profiler — это инструмент, который позволяет PHP-приложениям собирать данные о потребляемых ресурсах сервера, таких как память, процессорное время и операции ввода-вывода.

Полезные ссылки:

* [Blackfire site](https://www.blackfire.io/php)

-------------------------------------------------------------------------------------------------------

1. Bouras Aristides S. PHP and Algorithmic Thinking for the Complete Beginner, 2nd Edition. — CreateSpace Independent Publishing Platform, 2020. — 1094 p.
2. Engebreth G., Sahu S.K. PHP 8 Basics: For Programming and Web Development, Apress, 2023. — 335 p.
3. Guleria Pratiyush. PHP: Beginner’s Practical Guide, BPB Publications, 2021 — 109 p.
4. Learn PHP Basics of PHP Language, SrinivasIT.com., 2019. — 127 p.
5. Lentzner Remy. Getting started with PHP & MySQL: Professional training, Remylent, 2021. — 110 p.
6. Olsson M. PHP 8 Quick Scripting Reference. A Pocket Guide to PHP Web Scripting, 3rd ed. — Apress, 2020. — 188 p.
7. Pratt Logan. PHP: Advanced Guide to Learn the Realms of PHP Programming, Amazon.com Services LLC, 2021. — 212 p.
8. Sarabia R. Test-Driven Development with PHP 8: Build extensible, reliable, and maintainable enterprise-level applications using TDD and BDD with PHP, Birmingham: Packt Publishing, 2023. – 336 p.
9. William Emma. PHP and MySQL: PHP Programming and MySQL For Beginners, Amazon.com Services LLC., 2020. — 146 p.
10. Uzayr S. PHP: The Ultimate Guide, CRC Press, 2022. — 404 p.
11. Лукьянов Михаил. PHP. Полное руководство и справочник функций, СПб.: Наука и Техника, 2020. — 432 с.
12. Никсон Робин. Создаем динамические веб-сайты с помощью PHP, MySQL, JavaScript, CSS и HTML5, 6-е изд. — Пер. с англ. С. Черников. — СПБ.: Питер, 2023. — 832 с.: ил.

## Системы контроля версий

Системы контроля версий/исходного кода позволяют разработчикам отслеживать и контролировать изменения в коде с течением времени. Эти системы часто включают в себя возможность вносить атомарные изменения в код, осуществлять ветвление в определенных точек и сравнивать версий кода. Они позволяют определять кто, что, когда и почему были внесены изменения в код.

Полезные ссылки:

* [Git](https://git-scm.com/)
* [What is Version Control?](https://www.atlassian.com/git/tutorials/what-is-version-control)

### Git

[Git](https://git-scm.com/) — это бесплатная распределенная система контроля версиями с открытым исходным кодом, предназначенная для быстрой и эффективной работы с любыми проектами, от небольших до очень крупных.

Полезные ссылки:

* [Getting Started – About Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
* [Git & GitHub Crash Course For Beginners](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
* [Learn Git with Tutorials, News and Tips – Atlassian](https://www.atlassian.com/git)
* [Git Cheat Sheet](https://cs.fyi/guide/git-cheatsheet)

### Сервисы для хранения репозиториев

Работая в команде, вам часто бывает необходим отдельный удаленный сервер для размещения вашего кода, чтобы другие члены могли получить к нему доступ, добавлять свои собственные ветки и создавать или просматривать пул-реквесты. Эти сервисы часто включают в себя механизмы для отслеживания ошибок, ревью кода и функционал для непрерывной интеграции. Наиболее популярными вариантами являются: GitHub, GitLab, BitBucket и AWS CodeCommit.

Полезные ссылки:

* [Сравнение хостингов для проектов свободного программного обеспечения](https://ru.wikipedia.org/wiki/%D0%A1%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_%D1%85%D0%BE%D1%81%D1%82%D0%B8%D0%BD%D0%B3%D0%BE%D0%B2_%D0%B4%D0%BB%D1%8F_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BE%D0%B2_%D1%81%D0%B2%D0%BE%D0%B1%D0%BE%D0%B4%D0%BD%D0%BE%D0%B3%D0%BE_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D1%8F)
* [GitHub](https://github.com/features/)
* [GitLab](https://about.gitlab.com/)
* [BitBucket](https://bitbucket.org/product/guides/getting-started/overview)
* [How to choose the best source code repository](https://bitbucket.org/product/code-repository)

#### Github

GitHub — это провайдер интернет-хостинга для разработки программного обеспечения и контроля версий с использованием Git. Он предоставляет весь Git функционал в плане распределенной системы контроля и управления исходным кодом, а также обладает рядом индивидуальных, своих собственных возможностей.

Полезные ссылки:

* [GitHub Website](https://github.com/)
* [GitHub Documentation](https://docs.github.com/en/get-started/quickstart)
* [How to Use Git in a Professional Dev Team](https://ooloo.io/project/github-flow)
* [What is GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E)
* [Git vs. GitHub: Whats the difference?](https://www.youtube.com/watch?v=wpISo9TNjfU)
* [Git and GitHub for Beginners](https://www.youtube.com/watch?v=RGOj5yH7evk)
* [Git and GitHub – CS50 Beyond 2019](https://www.youtube.com/watch?v=eulnSXkhE7I)

#### GitLab

GitLab — провайдер интернет-хостинга для разработки программного обеспечения и контроля версий с использованием Git. Он предоставляет весь Git функционал в плане распределенной системы контроля и управления исходным кодом плюс ряд только ему присущих возможностей.

* [GitLab Website](https://gitlab.com/)
* [GitLab Documentation](https://docs.gitlab.com/)

#### Bitbucket

Bitbucket — это сервис для размещения и хранения исходного кода на основе Git, который является альтернативой, разработанной Atlassian, другим продуктам, таким как GitHub, GitLab и т. д.

Bitbucket предлагает следующие варианты хостинга: Bitbucket Cloud (серверы Atlassian), Bitbucket Server (локально у клиента) или Bitbucket Data Center (группа серверов в локальной или облачной среде клиента).

Полезные ссылки:

* [Bitbucket Website](https://bitbucket.org/product)
* [Getting started with Bitbucket](https://bitbucket.org/product/guides/basics/bitbucket-interface)
* [Using Git with Bitbucket Cloud](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
* [A brief overview of Bitbucket](https://bitbucket.org/product/guides/getting-started/overview#a-brief-overview-of-bitbucket)
* [Bitbucket tutorial | How to use Bitbucket Cloud](https://www.youtube.com/watch?v=M44nEyd_5To)
* [Bitbucket Tutorial | Bitbucket for Beginners](https://www.youtube.com/watch?v=i5T-DB8tb4A)

## Базы данных
### Реляционные базы данных

Реляционная база данных — это тип базы данных, которая хранит и предоставляет доступ к данным, связанным друг с другом. Реляционные базы данных хранят данные в виде набора таблиц. Связи между таблицами определяются с помощью внешних ключей. Внешний ключ — это уникальная ссылка из одной строки на другую строку в этой же или чаще всего другой таблице.

Полезные ссылки:

* [Что такое реляционная база данных?](https://aws.amazon.com/ru/relational-database/)
* [Relational Databases](https://www.ibm.com/cloud/learn/relational-databases)
* [51 Years of Relational Databases](https://learnsql.com/blog/codd-article-databases/)
* [Databases and SQL](https://www.edx.org/course/databases-5-sql)
* [Intro To Relational Databases](https://www.udacity.com/course/intro-to-relational-databases--ud197)
* [What is Relational Database](https://youtu.be/OqjJjpjDRLc)

#### PostgreSQL

PostgreSQL или Postgres, представляет собой бесплатную систему управления реляционными базами данных с открытым исходным кодом, в которой особое внимание уделяется расширяемости и совместимости с SQL.

Полезные ссылки:

* [PostgreSQL site](https://www.postgresql.org/)
* [Visit Dedicated PostgreSQL DBA Roadmap](https://roadmap.sh/postgresql-dba)
* [What is PostgreSQL](https://www.geeksforgeeks.org/what-is-postgresql-introduction/)
* [Learn PostgreSQL – Full Tutorial for Beginners](https://www.postgresqltutorial.com/)
* [Learn PostgreSQL Tutorial – Full Course for Beginners](https://www.youtube.com/watch?v=qw--VYLpxG4)
* [Postgres tutorial for Beginners](https://www.youtube.com/watch?v=eMIxuk0nOkU)

#### MySQL

MySQL — очень популярная система управления реляционными базами данных (RDBMS) с открытым исходным кодом. MySQL можно использовать как отдельный клиент или в сочетании с другими сервисами для подключения к базе данных. M в стеке LAMP означает MySQL; уже одно это должно дать представление о её распространенности.

Полезные ссылки:

* [MySQL site](https://www.mysql.com/)
* [W3Schools – MySQL tutorial](https://www.w3schools.com/mySQl/default.asp)
* [MySQL tutorial for beginners](https://www.youtube.com/watch?v=7S_tz1z_5bA)

#### MariaDB

MariaDB сервер — это ответвление MySQL сервера, разработанное сообществом. Основанная ключевыми членами оригинальной команды MySQL, MariaDB активно работает со сторонними разработчиками, чтобы создать стабильный, с наибольшими функциональными возможностями, с разумным подходом к лицензированию SQL-сервер с открытым исходным кодом в отрасли. MariaDB была создана с намерением стать более универсальной версией MySQL с возможностью замены налету с минимальными исправлениями.

Полезные ссылки:

* [MariaDB site](https://mariadb.org/)
* [MariaDB vs MySQL](https://www.guru99.com/mariadb-vs-mysql.html)
* [W3Schools – MariaDB tutorial](https://www.w3schools.blog/mariadb-tutorial)
* [MariaDB Tutorial For Beginners in One Hour](https://www.youtube.com/watch?v=_AMj02sANpI)

#### MS SQL

MS SQL (или Microsoft SQL Server) — это разработанная Microsoft система управления реляционными базами данных (RDBMS). MS SQL использует язык запросов T-SQL (Transact-SQL) для взаимодействия с реляционными базами данных. Существует множество различных версий и редакций MS SQL.

Полезные ссылки:

* [MS SQL website](https://www.microsoft.com/en-ca/sql-server/)
* [MS SQL Википедия](https://ru.wikipedia.org/wiki/Microsoft_SQL_Server)
* [Tutorials for SQL Server](https://docs.microsoft.com/en-us/sql/sql-server/tutorials-for-sql-server-2016?view=sql-server-ver15)
* [SQL Server tutorial for beginners](https://www.youtube.com/watch?v=-EPMOaV7h_Q)

#### Oracle

Сервер базы данных Oracle, Oracle RDBMS или просто Oracle, является ведущей в мире системой управления реляционными базами данных, созданной корпорацией Oracle.

Полезные ссылки:

* [Oracle site](https://www.oracle.com/database/)
* [Official Docs](https://docs.oracle.com/en/database/index.html)
* [Oracle SQL Tutorial for Beginners](https://www.youtube.com/watch?v=ObbNGhcxXJA)

### NoSQL базы данных

NoSQL базы данных предлагают хранить и извлекать данные иначе, чем «традиционные» реляционные базы данных. Базы данных NoSQL обычно больше ориентированы на горизонтальное масштабирование, согласованность в конечном счёте, скорость и гибкость и чаще всего используются для приложений с большим объёмом данных и потоковых приложений в реальном времени. NoSQL часто называют BASE (**B**asically **A**vailable (Базовая доступность), **S**oft-state (Неустойчивое состояние), **E**ventually consistent (Согласованность в конечном счёте)) системами и они являются противоположностью SQL/реляционным системам, где основопологающим является принцип ACID (**A**tomicity (Атомарность), **C**onsistency (Согласованность), **I**solation (Изоляция), **D**urability (Устойчивость)). Чаще всего в NoSQL используются следующие структуры для хранения данных: пара «ключ‑значение», «широкий столбец», граф и документ.

Полезные ссылки:

* [Что такое базы данных NoSQL?](https://aws.amazon.com/ru/nosql/)
* [NoSQL Explained](https://www.mongodb.com/nosql-explained)
* [How do NoSQL Databases work](https://www.youtube.com/watch?v=0buKQHokLK8)
* [SQL vs NoSQL Explained](https://www.youtube.com/watch?v=ruz-vK8IesE)

#### Документоориентированная база данных: MongoDB, CouchDB

MongoDB — это кросс-платформенная, документоориентированная система управления базами данных с открытым исходным кодом. MongoDB относится к
NoSQL системам управления базами данных и использует JSON-подобные документы с произвольной структурой. MongoDB разработана MongoDB Inc. и распространяется под лицензией Server Side Public License (SSPL).

Полезные ссылки:

* [Документоориентированная СУБД](https://ru.wikipedia.org/wiki/%D0%94%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%B0%D1%8F_%D0%A1%D0%A3%D0%91%D0%94)
* [MongoDB Википедия](https://ru.wikipedia.org/wiki/MongoDB)
* [CouchDB Википедия](https://ru.wikipedia.org/wiki/CouchDB)
* [MongoDB Website](https://www.mongodb.com/)
* [MongoDB Documentation](https://docs.mongodb.com/)
* [MongoDB Online Sandbox](https://mongoplayground.net/)
* [Learning Path for MongoDB Developers](https://learn.mongodb.com/catalog)
* [Dynamo DB Docs](https://docs.aws.amazon.com/dynamodb/index.html)
* [Official Developers Guide](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

#### База данных с «широкими столбцами»: Cassandra, HBase

База данных с «широкими столбцами» (иногда называемая колоночной, столбчатой) похожа на реляционные БД. Как и реляционные, она хранит данные,
в таблицах, строках и столбцах. Однако в отличие от реляционных баз данных здесь каждая строка может иметь разные названия и формат столбцов.
Столбчатую БД можно считать двумерной базой данных типа «ключ-значение». Одной из таких СУБД является **Apache Cassandra**.

БД с «широкими столбцами» поддерживающими «семейства столбцов», также называют базами данных «семейства столбцов».

**Замечание**. Не путайте столбчатые БД с [столбцовыми БД](https://ru.wikipedia.org/wiki/%D0%A1%D1%82%D0%BE%D0%BB%D0%B1%D1%86%D0%BE%D0%B2%D0%BE%D0%B5_%D1%85%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5). Это два разных понятия!

Полезные ссылки:

* [База данных с «широкими столбцами»](https://aws.amazon.com/ru/nosql/columnar/)
* [Cassandra Википедия](https://ru.wikipedia.org/wiki/Apache_Cassandra)
* [Apache Cassandra](https://cassandra.apache.org/_/index.html)
* [Apache Cassandra Database – Full Course for Beginners](https://www.youtube.com/watch?v=J-cSy5MeMOA)
* [HBase Википедия](https://ru.wikipedia.org/wiki/HBase)

#### База данных временных рядов: InfluxDB, TimescaleDB

InfluxDB создавалась с нуля как специализированная база данных временных рядов, т. е. не была перепрофилирована в неё. Время было частью БД
с самого начала. InfluxDB является частью комплексной платформы, которая поддерживает сбор, хранение, мониторинг, визуализацию и оповещение о данных временных рядов. Это гораздо больше, чем просто база данных временных рядов.

Полезные ссылки:

* [Что такое базы данных временных рядов](https://wiki.merionet.ru/servernye-resheniya/110/chto-takoe-bazy-dannyh-vremennyh-ryadov/)
* [InfluxDB website](https://www.influxdata.com/)
* [Time series database](https://www.influxdata.com/time-series-database/)
* [TimescaleDB website](https://www.timescale.com/)

#### База данных реального времени: Firebase, RethinkDB

База данных реального времени в широком смысле определяется как хранилище данных, предназначенное для сбора, обработки и/или изменения входящей последовательности точек данных (т. е. потока данных) в реальном времени, как правило, сразу после создания данных.

Полезные ссылки:

* [База данных Firebase в реальном времени](https://firebase.google.com/docs/database?hl=ru)
* [Что такое Firebase (realtime database)](https://webkyrs.info/page/chto-takoe-firebase-realtime-database)
* [RethinkDB Википедия](https://ru.wikipedia.org/wiki/RethinkDB)

#### Графовая база данных: Neo4j

Графовая база данных хранит узлы и отношения вместо таблиц или документов. Данные хранятся так, как если бы вы делали наброски идей на доске. Ваши данные хранятся не ограничиваясь заранее определенной моделью, что позволяет сильно расширить способы обработки и возможности их использования.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%93%D1%80%D0%B0%D1%84%D0%BE%D0%B2%D0%B0%D1%8F_%D0%B1%D0%B0%D0%B7%D0%B0_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)
* [Neo4j Википедия](https://ru.wikipedia.org/wiki/Neo4j)
* [What is a Graph Database?](https://neo4j.com/developer/graph-database/)
* [Graph Databases VS Relational Databases](https://www.freecodecamp.org/news/graph-database-vs-relational-database/)

#### База данных «ключ — значение»: Redis, DynamoDB

База данных «ключ-значение» (база данных KV) — это тип базы данных, в которой данные хранятся в виде набора пар «ключ-значение». В базе данных KV каждая часть данных идентифицируется уникальным ключом, а значением являются данные, связанные с этим ключом.

Базы данных KV предназначены для быстрого и эффективного хранения и извлечения данных, и они часто используются в приложениях, требующих высокой производительности и низкой задержки. Они особенно хорошо подходят для хранения больших объемов неструктурированных данных, таких как данные логов и профили пользователей.

Примерами популярных базы данных KV являются Redis, Memcached и LevelDB. Эти базы данных часто используются в сочетании с другими типами баз данных, такими как реляционные базы данных или документоориентированные базы данных, обеспечивая совершенное и масштабируемое решение для хранения данных.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%91%D0%B0%D0%B7%D0%B0_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85_%C2%AB%D0%BA%D0%BB%D1%8E%D1%87_%E2%80%94_%D0%B7%D0%BD%D0%B0%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%C2%BB)
* [Redis Википедия](https://ru.wikipedia.org/wiki/Redis)
* [DynamoDB Википедия](https://ru.wikipedia.org/wiki/DynamoDB)

### Теоретические основы
#### ORMs

Объектно-реляционное отображение (Object-Relational Mapping, ORM) — это технология, который позволяет вам запрашивать и манипулировать данными из базы данных, используя объектно-ориентированную концепцию. Говоря об ORM, большинство людей имеют в виду библиотеку, которая реализует технологию объектно-реляционного отображения, отсюда и фраза «ORM».

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/ORM)
* [What is an ORM and how should I use it?](https://stackoverflow.com/questions/1279613/what-is-an-orm-how-does-it-work-and-how-should-i-use-one)

#### ACID

ACID — это четыре свойства систем управления реляционными базами данных, которые гарантируют надёжное выполнение транзакций. Это аббревиатура, обозначающая, что БД обладает следующими четырьмя свойствами: атомарность, согласованность, изоляция и устойчивость.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/ACID)
* [What is ACID Compliant Database?](https://retool.com/blog/whats-an-acid-compliant-database/)
* [What is ACID Compliance?: Atomicity, Consistency, Isolation](https://fauna.com/blog/what-is-acid-compliance-atomicity-consistency-isolation)
* [ACID Explained: Atomic, Consistent, Isolated & Durable](https://www.youtube.com/watch?v=yaQ5YMWkxq4)

#### Транзакции

Простыми словами, транзакция базы данных — это последовательность из нескольких операций, выполняемых в базе данных. При этом они являются
единой логической единицей работы — выполняются полностью или не выполняются вовсе. Иначе говоря, никогда не бывает так, чтобы выполнялась только часть операций и были зафиксированы результаты.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%A2%D1%80%D0%B0%D0%BD%D0%B7%D0%B0%D0%BA%D1%86%D0%B8%D1%8F_(%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B0))
* [What are Transactions?](https://fauna.com/blog/database-transaction)

#### N+1 проблема

Проблема с N+1 запросом возникает, когда ваш код выполняет N дополнительных операций для получения тех же данных, которые могли быть получены путём выполнения основного запроса

Полезные ссылки:

* [What is the "N+1 selects problem" in ORM (Object-Relational Mapping)?](https://stackoverflow.com/questions/97197/what-is-the-n1-selects-problem-in-orm-object-relational-mapping)
* [Решение проблемы N+1 запроса без увеличения потребления памяти в Laravel](https://habr.com/ru/articles/508544/)
* [In Detail Explanation of N+1 Problem](https://medium.com/doctolib/understanding-and-fixing-n-1-query-30623109fe89)

#### Нормализация

Нормализация базы данных — это процесс структурирования реляционной базы данных, который приводит её последовательно к так называемым нормальным формам, с целью уменьшения избыточности данных и улучшения целостности данных. Впервые она была предложена Эдгаром Ф. Коддом как часть его реляционной модели.

Нормализация приводит к организации столбцов (атрибутов) и таблиц (отношений) базы данных таким образом, чтобы их зависимости должным образом соблюдались благодаря ограничениям целостности базы данных. Это достигается путем применения некоторых формальных правил в процессе синтеза (создания новой структуры базы данных) или декомпозиции (улучшения структуры существующей базы данных).

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%9D%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%84%D0%BE%D1%80%D0%BC%D0%B0)
* [What is Normalization in DBMS (SQL)? 1NF, 2NF, 3NF, BCNF Database with Example](https://www.guru99.com/database-normalization.html)
* [Basic Concept of Database Normalization](https://www.youtube.com/watch?v=xoTyrdT9SZI)

#### Сбои, возникающие при работе БД

Существует различные сбои, которые могут возникнуть в базе данных, в том числе:

* Конфликт при чтении: происходит, когда несколько клиентов или процессов пытаются одновременно прочитать данные из одного и того же места в базе данных, что может привести к задержкам или ошибкам.
* Конфликт при записи: происходит, когда несколько клиентов или процессов пытаются одновременно записать данные в одно и то же место в базе данных, что может привести к задержкам или ошибкам.
* «Неуправляемое стадо»: происходит, когда большое количество клиентов или процессов пытаются одновременно получить доступ к одному и тому же ресурсу, что может привести к исчерпанию ресурсов и снижению производительности.
* Каскад: происходит, когда сбой в одной части системы базы данных вызывает цепную реакцию, которая приводит к сбоям в других частях системы.
* Взаимная блокировка: происходит, когда две или более транзакций ждут друг друга, чтобы снять блокировку с ресурса, что приводит к их остановке.
* Повреждение: происходит, когда данные в базе данных повреждаются, что может привести к ошибкам или неожиданным результатам при чтении или записи в базу данных.
* Аппаратный сбой: происходит, когда аппаратные компоненты, такие как диски или память, выходят из строя, что может привести к потере или повреждению данных.
* Программный сбой: происходит, когда программные компоненты, такие как система управления базами данных или приложение, выходят из строя, что может привести к ошибкам или неожиданным результатам.
* Сбой сети: происходит, когда теряется сетевое соединение между базой данных и клиентом, что может привести к ошибкам или тайм-аутам при попытке доступа к базе данных.
* Атака типа «отказ в обслуживании» (DoS): происходит, когда злоумышленник пытается перегрузить базу данных запросами, что приводит к истощению ресурсов и снижению производительности.

#### Анализ производительности

Существует несколько способов собрать и проанализировать производительность базы данных:

* Мониторинг производительности системы. Вы можете использовать такие инструменты, как диспетчер задач Windows или команду top в Unix/Linux, для мониторинга производительности сервера базы данных. Эти инструменты позволяют увидеть общее использование ЦП, памяти и диска в системе, что может помочь выявить все проблемные места в потребляемых ресурсах.
* Используйте специальные инструменты для баз данных. Большинство систем управления базами данных (СУБД) имеют собственные инструменты для мониторинга производительности. Например, в Microsoft SQL Server существует SQL Server Management Studio (SSMS) и динамическое административное представление sys.dm_os_wait_stats, а в Oracle — Oracle Enterprise Manager и представление v$waitstat. Эти инструменты позволяют просматривать определенные показатели производительности, такие как количество времени, затраченное на ожидание при блокировках, или количество физических операций чтения и записи.
* Используйте сторонние инструменты: существует также несколько сторонних инструментов, которые могут помочь вам проанализировать производительность базы данных. Например, SolarWinds Database Performance Analyzer, Quest Software Foglight и Redgate SQL Monitor. Эти инструменты часто обеспечивают более глубокий анализ производительности и могут помочь вам выявить конкретные проблемы или узкие места.
* Анализ медленных запросов. Если у вас есть определенные запросы, которые выполняются медленно, вы можете использовать такие инструменты, как EXPLAIN PLAN или SHOW PLAN в MySQL или SQL Server, чтобы просмотреть план выполнения запроса и выявить возможные проблемы. Вы также можете использовать такие инструменты, как лог медленных запросов MySQL или SQL Server Profiler, для регистрации медленных запросов и их дальнейшего анализа.
* Мониторинг производительности приложения. Если у вас возникли проблемы с производительностью определенного приложения, использующего базу данных, вы можете использовать такие инструменты, как Application Insights или New Relic, для мониторинга производительности приложения и выявления любых проблем, которые могут быть связаны с базой данных.

Кроме того, ознакомьтесь с документацией базы данных, которую вы используете.

#### Индексы и как они работают

Индекс — это структура данных, создаваемая и задаваемая для существующей таблицы, которая по сути просматривает вашу таблицу и пытается проанализировать и обобщить данные, чтобы ускорить работу с ней.

Полезные ссылки:

* [Википедия](http://ru.wikipedia.org/wiki/%D0%98%D0%BD%D0%B4%D0%B5%D0%BA%D1%81_(%D0%B1%D0%B0%D0%B7%D1%8B_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85))
* [Что такое индексы базы данных (для начинающих)?](https://im-cloud.ru/blog/chto-takoe-indeksy-bazy-dannyh-dlja-nachinajushhih/)
* [An in-depth look at Database Indexing](https://www.freecodecamp.org/news/database-indexing-at-a-glance-bb50809d48bd/)
* [Database Indexing Explained](https://www.youtube.com/watch?v=-qNSXK7s7_w)

#### Репликация данных

Репликация данных — это процесс, с помощью которого данные, находящиеся на физическом или виртуальном сервере (серверах) или облачном инстансе (основной инстанс), непрерывно реплицируются или копируются на вторичный сервер (серверы) или облачный инстанс (резервный инстанс). Компании реплицируют данные для поддержки высокой доступности, резервного копирования и/или аварийного восстановления.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%BF%D0%BB%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F_(%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D0%BA%D0%B0))
* [What is Data Replication?](https://youtu.be/fUrKt-AQYtE)

#### Стратегии шардинга

Стратегия шардинга (сегментирования) — это метод разделения большого набора данных на более мелкие фрагменты (логический сегмент), в котором мы разносим эти фрагменты по разным машинам/узлам базы данных, чтобы распределить нагрузку трафика. Это хороший способ улучшения масштабируемости приложения. Многие базы данных поддерживают шардинг (сегментирование), но не все.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D0%B3%D0%BC%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_(%D0%B1%D0%B0%D0%B7%D1%8B_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85))
* [System Design Interview Concepts – Database Sharding](https://www.acodersjourney.com/database-sharding/)
* [Database Sharding – System Design Interview Concept](https://www.geeksforgeeks.org/database-sharding-a-system-design-concept/)
* [How sharding a database can make it faster](https://stackoverflow.blog/2022/03/14/how-sharding-a-database-can-make-it-faster/)

#### Теорема CAP

CAP — это акроним, расшифровывающийся как Consistency (согласованность данных), Availability (доступность) и Partition Tolerance (устойчивость к разделению). Согласно теореме CAP, любая распределенная система может гарантировать только два из трех свойств в любой момент времени. Невозможно обеспечить наличие всех трёх свойств одновременно.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%A2%D0%B5%D0%BE%D1%80%D0%B5%D0%BC%D0%B0_CAP)
* [What is CAP Theorem?](https://www.bmc.com/blogs/cap-theorem/)
* [An Illustrated Proof of the CAP Theorem](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)
* [CAP Theorem and its applications in NoSQL Databases](https://www.ibm.com/uk-en/cloud/learn/cap-theorem)
* [What is CAP Theorem?](https://www.youtube.com/watch?v=_RbsFXWRZ10)

## Изучаем API
### REST

REST, **Re**presentational **S**tate **T**ransfer или «передача репрезентативного состояния» — это архитектурный стиль, определяющий стандарты между компьютерными системами в Интернете, что упрощает взаимодействие таких систем друг с другом.

Полезные ссылки:

* [Representational State Transfer (REST)](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)
* [Википедия](https://ru.wikipedia.org/wiki/REST)
* [What is REST?](https://www.codecademy.com/article/what-is-rest)
* [What is a REST API?](https://www.redhat.com/en/topics/api/what-is-a-rest-api)
* [Roy Fieldings dissertation chapter, Representational State Transfer (REST)](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)
* [Learn REST: A RESTful Tutorial](https://restapitutorial.com/)

### JSON APIs

JSON или **J**ava**S**cript **O**bject **N**otation — это формат кодирования, разработанный для устранения необходимости в специальном коде для каждого приложения, чтобы связываться с серверами, которые взаимодействуют определенным образом. JSON API модуль предоставляет реализацию для хранилищ и структур данных.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/JSON)
* [A specification for building APIs in JSON](https://jsonapi.org/)
* [JSON API Implementations](https://jsonapi.org/implementations/)
* [JSON API: Explained in 4 minutes](https://www.youtube.com/watch?v=N-4prIh7t38)

### SOAP

Простой протокол доступа к объектам (SOAP, **S**imple **O**bject **A**ccess **P**rotocol) — это протокол обмена сообщениями для обмена информацией между системами и приложениями. Что касается интерфейсов прикладного программирования (API), SOAP API разрабатывается более структурированным и формализованным образом. Сообщения SOAP могут передаваться по различным протоколам более низкого уровня, включая, связанный с веб, протокол передачи гипертекста (HTTP).

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/SOAP)
* [w3school SOAP explanation](https://www.w3schools.com/xml/xml_soap.asp)

### gRPC

gRPC — это высокопроизводительный универсальный RPC фреймворк с открытым исходным кодом.

RPC (**R**emote **P**rocedure **C**all) означает удаленный вызов процедур, и продолжаются споры о том, что означает буква g. RPC — это протокол, который позволяет программе выполнять процедуру другой программы, расположенной на другом компьютере. Большим преимуществом является то, что разработчику не нужно писать код, отвечающий за детали удаленного взаимодействия. Удаленная процедура вызывается так же, как и любая другая функция. В то же время клиент и сервер могут быть написаны на разных языках.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/GRPC)
* [gRPC Website](https://grpc.io/)
* [gRPC Docs](https://grpc.io/docs/)
* [What Is GRPC?](https://www.wallarm.com/what/the-concept-of-grpc)
* [What Is GRPC?](https://www.youtube.com/watch?v=hVrwuMnCtok)

### GraphQL

GraphQL — это язык запросов и среда выполнения для API (интерфейсов прикладного программирования). Он предназначен для предоставления клиентам гибкого и эффективного способа запроса данных с серверов и часто используется в качестве альтернативы REST («передача репрезентативного состояния») API-интерфейсам.

Одной из основных особенностей GraphQL является возможность указывать именно те данные, которые необходимы, а не получать фиксированный набор данных от конечной точки. Это позволяет клиентам запрашивать только те данные, которые им нужны, и уменьшает объем данных, которые необходимо передать по сети.

GraphQL предоставляет способ определения структуры данных, возвращаемых сервером, что позволяет клиентам запрашивать данные предсказуемым и гибким способом. Это упрощает создание и поддержку клиентских приложений, зависящих от данных с сервера.

GraphQL широко используется в современных веб и мобильных приложениях; поддерживается большим и активным сообществом разработчиков.

Полезные ссылки:

* [GraphQL site](https://graphql.org/)

### HATEOAS

HATEOAS — это акроним от **H**ypermedia **A**s **T**he **E**ngine **O**f **A**pplication **S**tate. Это концепция, заключающаяся в том, что при отправке информации через RESTful API полученный документ должен содержать всё, что нужно клиенту для анализа и использования данных, т. е. ему не нужно связываться с какой-либо другой конечной точкой, явно не упомянутой в документе.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/HATEOAS)
* [Oktane17: Designing Beautiful REST + JSON APIs (3:56 – 5:57)](https://youtu.be/MiOSzpfP1Ww?t=236)

### Open API Specs и Swagger

Спецификация OpenAPI (OpenAPI Specification, OAS) определяет стандартный, не зависящий от языка интерфейс для RESTful API, который позволяет людям и машинам обнаруживать и понимать возможности сервиса без доступа к исходному коду, документации или изучения сетевого трафика. При правильном определении потребитель может понимать и взаимодействовать с удаленным сервисом с минимальным количеством кода, реализующего логику.

Затем OpenAPI спецификация может использоваться инструментами создания документации для описания API, инструментами генерации кода для создания серверов и клиентов на различных языках программирования, инструментами тестирования, кроме того существует множество других вариантов применения.

Полезные ссылки:

* [Знакомство со спецификациями OpenAPI и Swagger](https://starkovden.github.io/introduction-openapi-and-swagger.html)
* [OpenAPI Specification Website](https://swagger.io/specification/)
* [Open API Live Editor](https://swagger.io/tools/swagger-editor/)
* [Official training guide](https://www.youtube.com/watch?v=6kwmW_p_Tig)
* [OpenAPI 3.0: How to Design and Document APIs with the Latest OpenAPI Specification 3.0](https://www.youtube.com/watch?v=6kwmW_p_Tig)

### Аутентификация

Процесс аутентификации API проверяет подлинность клиента, пытающегося установить соединение, используя протокол аутентификации. Протокол отправляет учетные данные от удаленного клиента, запрашивающего подключение к серверу удаленного доступа, в текстовом или зашифрованном виде. Затем сервер определяет, может ли он предоставить доступ к этому удаленному клиенту или нет.

Ниже представлен список распространенных способов аутентификации:

* JWT-аутентификация
* Аутентификация, используя токенов
* Аутентификация, используя сессии
* Базовая аутентификация
* OAuth — Open Authorization — открытый протокол (схема) авторизации
* SSO — Single Sign On — Технология единого входа

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/%D0%90%D1%83%D1%82%D0%B5%D0%BD%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F)
* [User Authentication: Understanding the Basics & Top Tips](https://swoopnow.com/user-authentication/)
* [An overview about authentication methods](https://betterprogramming.pub/how-do-you-authenticate-mate-f2b70904cc3a)
* [SSO – Single Sign On](https://roadmap.sh/guides/sso)
* [OAuth – Open Authorization](https://roadmap.sh/guides/oauth)
* [JWT Authentication](https://roadmap.sh/guides/jwt-authentication)
* [Token Based Authentication](https://roadmap.sh/guides/token-authentication)
* [Session Based Authentication](https://roadmap.sh/guides/session-authentication)
* [Basic Authentication](https://roadmap.sh/guides/basic-authentication)

#### Основанная на cookies

Cookies — это фрагменты данных, используемый для идентификации пользователя и его предпочтений. Браузер передаёт cookie на сервер каждый раз, когда запрашивается страница. Определенные cookies, такие как HTTP cookies, используются для выполнения аутентификации на основе cookie для сохранения [сеанса](https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D0%B0%D0%BD%D1%81_(%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B0)) для каждого пользователя.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/Cookie)
* [How does cookie-based authentication work?](https://stackoverflow.com/questions/17769011/how-does-cookie-based-authentication-work)

#### OAuth

OAuth расшифровывается как **O**pen **Auth**orization и является открытым стандартом авторизации. Он применяется для авторизации устройств, API, серверов и приложений с использованием токенов доступа, а не учетных данных пользователя, что также называют «безопасным делегированным доступом».

В самом простом своём варианте OAuth делегирует аутентификацию таким сервисам, как Facebook, Amazon, Twitter, и разрешает сторонним приложениям получать доступ к учетной записи пользователя **без необходимости** ввода логина и пароля.

Он в основном используется для REST/APIs и предоставляет доступ только к ограниченному объему пользовательских данных.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/OAuth)
* [Okta – What the Heck is OAuth](https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth)
* [DigitalOcean – An Introduction to OAuth 2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2)
* [What is OAuth really all about](https://www.youtube.com/watch?v=t4-416mg6iU)
* [OAuth 2.0: An Overview](https://www.youtube.com/watch?v=CPbvxxslDTU)

#### Базовая аутентификация

Исходя из названия «Базовая аутентификация», не следует путать базовую аутентификацию со стандартной аутентификацией по имени пользователя и паролю. Базовая аутентификация является частью спецификации HTTP, и более подробную информацию о ней можно [найти в стандарте RFC7617](https://www.rfc-editor.org/rfc/rfc7617.html).

Поскольку это часть спецификаций HTTP, все браузеры имеют встроенную поддержку «HTTP базовой аутентификации».

Полезные ссылки:

* [Википедия](https://en.wikipedia.org/wiki/Basic_access_authentication)
* [HTTP Basic Authentication](https://roadmap.sh/guides/http-basic-authentication)
* [Illustrated HTTP Basic Authentication](https://www.youtube.com/watch?v=mwccHwUn7Gc)

#### Аутентификация, используя токены

Аутентификация, используя токены — это протокол, который позволяет пользователям подтверждать свою личность и взамен получать уникальный токен доступа. В течение срока действия токена пользователи затем получают доступ к веб-сайту или приложению, для которого был выпущен токен, вместо того, чтобы повторно вводить учетные данные каждый раз, когда они переходят на веб-страницу, приложение или любой ресурс, защищенный тем же токеном.

Токены аутентификации работают так же как прокомпостированный билет в общественном транспорте. Пользователь сохраняет доступ до тех пор, пока токен остается валидным, действительным, действующим (пассажир может пользователься услугами общественного транспорта, не опасаясь встречи с контролёром, пока у него на руках прокомпостированный билет). Как только пользователь выходит из системы или закрывает приложение, токен становится недействительным (пассажир выходит из общественного транспорта, прокомпостированный билет нельзя использовать повторно, нужно покупать новый).

Аутентификация, используя токены, отличается от традиционных методов аутентификации на основе пароля или сервера. Токены предлагают дополнительный уровень безопасности, а администраторы имеют большую полноту контроля над каждым действием и транзакцией.

Но использование токенов требует некоторого ноу-хау при написании кода. Большинство разработчиков быстро осваивают методологии, но существует кривая обучения.

Полезные ссылки:

* [Understanding Token-Based Authentication: A Detailed Review](https://frontegg.com/blog/token-based-authentication)
* [What Is Token-Based Authentication?](https://www.okta.com/identity-101/what-is-token-based-authentication/)

##### JWT

JWT сокращение от **J**SON **W**eb **T**oken — это открытый стандарт/методология шифрования с использованием токенов, который используется для безопасной передачи информации в виде JSON объекта. Клиенты и серверы используют JWT для безопасного обмена информацией, при этом JWT содержит закодированные JSON объекты и claims. JWT токены создавались таким образом, чтобы быть компактными, безопасными для использования в URL-адресах и идеально подходить в тех случаях, где используется SSO (Single Sign On — Технология единого входа).

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/JSON_Web_Token)
* [Про токены, JSON Web Tokens (JWT), аутентификацию и авторизацию](https://gist.github.com/zmts/802dc9c3510d79fd40f9dc38a12bccfc)
* [LocalStorage vs Cookies: All You Need To Know About Storing JWT Tokens Securely in The Front-End](https://dev.to/cotter/localstorage-vs-cookies-all-you-need-to-know-about-storing-jwt-tokens-securely-in-the-front-end-15id)
* [The JWT Handbook by Sebastián E. Peyrott, Auth0 Inc.](https://auth0.com/resources/ebooks/jwt-handbook)
* [jwt.io Website](https://jwt.io/)
* [Introduction to JSON Web Tokens](https://jwt.io/introduction)
* [What is JWT?](https://www.akana.com/blog/what-is-jwt)
* [What Is JWT and Why Should You Use JWT](https://www.youtube.com/watch?v=7Q17ubqLfaM)
* [What is JWT? JSON Web Token Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

#### OpenID

OpenID — это протокол, который использует механизмы авторизации и аутентификации OAuth 2.0 и в настоящее время широко применяется многими провайдерами идентификационных данных в Интернете. Он решает проблему необходимости обмена личной информацией пользователя между множеством различных веб-сервисов (например, интернет-магазинами, форумами и т. д.).

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/OpenID)
* [Official Website](https://openid.net/)
* [What is OpenID](https://openid.net/connect/)
* [OAuth vs OpenID](https://securew2.com/blog/oauth-vs-openid-which-is-better)
* [An Illustrated Guide to OAuth and OpenID Connect](https://www.youtube.com/watch?v=t18YB3xDfXI)

#### SAML

SAML (**S**ecurity **A**ssertion **M**arkup **L**anguage) расшифровывается как язык разметки декларации безопасности. Это стандарт на основе XML для обмена данными аутентификации и авторизации между сторонами, в частности между провайдером идентификационных данных (identity provider, IdP) и провайдером сервиса (service provider, SP). В системе на основе SAML пользователь запрашивает доступ к защищенному ресурсу.
Провайдер сервиса просит провайдера идентификационных данных аутентифицировать пользователя и подтвердить, предоставлен ли ему доступ к ресурсу.

##### Преимущества SAML

К преимуществам использования SAML относят следующие:

* Технология единого входа (SSO): пользователи могут один раз войти в IdP и получить доступ к нескольким провайдерам сервисов без необходимости повторной аутентификации.
* Улучшенная безопасность: провайдеру сервиса не требуется хранить пароли и учетные данные пользователей и управлять ими, что снижает потенциальные векторы атак.
* Повышенная эффективность: поскольку пользователям больше не нужно хранить несколько наборов учётных данных, управление доступом становится проще как для пользователя, так и для системных администраторов.
* Совместимость: SAML позволяет широкому спектру приложений работать вместе, независимо от используемых технологий или платформы.

##### SAML-компоненты

В архитектуре SAML задействованы три основных компонента:

1. **Провайдер идентификационных данных (IdP)**: объект, который управляет идентификационными данными пользователей и аутентифицирует их, предоставляя токены безопасности, также называемые декларациями.
2. **Провайдер сервиса (SP)**: объект, который предоставляет сервис (например, веб-приложение или API) и полагается на поставщика идентификационных данных для аутентификации пользователей и предоставления/отказа в доступе к ресурсам.
3. **Пользователь/Выгодополучатель**: конечный пользователь, которому требуется доступ к сервису, предоставляемый провайдером сервиса.

##### Последовательность действий при SAML

Процесс аутентификации SAML состоит из следующих шагов:

1. Пользователь запрашивает доступ к защищенному ресурсу у провайдером сервиса.
2. Если пользователь ещё не аутентифицирован, провайдер сервис генерирует и отправляет запрос аутентификации SAML провайдеру идентификационных данных.
3. Провайдер идентификационных данных аутентифицирует пользователя (используя, например, имя пользователя и пароль, многофакторную аутентификацию или другой метод).
4. Провайдер идентификационных данных создает ответ SAML, который включает в себя сведения о пользователе и декларирует, авторизован ли пользователь для получения доступа к запрошенному ресурсу.
5. Ответ SAML отправляется обратно провайдеру сервиса, как правило, через веб-браузер пользователя или API клиент.
6. Провайдер сервиса обрабатывает ответ SAML, извлекает необходимую информацию и предоставляет или запрещает доступ пользователю на основе декларации провайдера идентификационных данных.

С помощью SAML вы можете оптимизировать аутентификацию и авторизацию пользователей в различных приложениях и системах, повышая удобство работы пользователей и повышая общую безопасность бекэнда.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/SAML)
* [Что такое SAML аутентификация и кому она нужна?](https://habr.com/ru/company/gemaltorussia/blog/322316/)

## Кэширование

Кэширование — это метод хранения часто используемых данных или информации в локальной памяти в течение определенного периода времени. Таким образом, в следующий раз, когда клиент запрашивает ту же информацию, вместо извлечения информации из базы данных она выдаётся из локальной памяти. Основное преимущество кэширования заключается в том, что оно повышает производительность за счет снижения нагрузки, связанной с логикой обработки запроса.

### CDN

Сервис сети доставки содержимого (Content Delivery Network (CDN)) предназначен для обеспечения высокой доступности и повышения производительности веб-сайтов. Это достигается за счет быстрой доставки ресурсов и содержимого веб-сайта, как правило, с помощью географически более близко расположенных серверов относительно клиентов, запрашивающих информацию. Все платные CDN (Amazon CloudFront, Akamai, CloudFlare и Fastly) предоставляют серверы по всему миру, которые можно использовать для этой цели. Отправка ресурсов и содержимого через CDN снижает нагрузку на хостинге веб-сайтов, обеспечивает дополнительный уровень кэширования для уменьшения возможных сбоев и может также повысить безопасность веб-сайта.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/Content_Delivery_Network)
* [CloudFlare – What is a CDN? | How do CDNs work?](https://www.cloudflare.com/en-ca/learning/cdn/what-is-a-cdn/)
* [What is Cloud CDN?](https://www.youtube.com/watch?v=841kyd_mfH0)
* [What is a Content Delivery Network (CDN)?](https://www.youtube.com/watch?v=Bsq5cKkS33I)

### Кэш на серверном уровне

Помимо настройки правильных заголовков ответа и обработки заголовков запроса, существует множество разных моментов, которые вы могли бы улучшить на стороне сервера и приложения.

Первый подход к более быстрым ответам и экономии ресурсов — настройка кэш-сервера между приложением и клиентом.

Такие инструменты, как Varnish, Squid и nginx кэшируют изображения, скрипты и прочее содержимое, которое требуется пользователям.

Кэширование на стороне сервера временно сохраняет веб-файлы и данные на исходном сервере для последующего повторного использования.

Когда пользователь впервые запрашивает веб-страницу, проходит обычный процесс получения данных с сервера и создается или собирается веб-страница веб-сайта. После выполнения запроса и отправки ответа сервер копирует веб-страницу и сохраняет её в виде кеша.

В следующий раз, когда пользователь повторно посещает веб-сайт, он загружает уже сохраненную или кэшированную копию веб-страницы, что ускоряет его работу.

Полезные ссылки:

* [Кэш на серверном уровне](https://tproger.ru/translations/cache-levels-on-the-web/)
* [Server-side caching](https://www.starwindsoftware.com/resource-library/server-side-caching/)
* [Server-side caching and Client-side caching](https://www.codingninjas.com/codestudio/library/server-side-caching-and-client-side-caching)

#### используя Redis

Redis — это хранилище структур данных в памяти с открытым исходным кодом (распространяемое под лицензией BSD), используемое в качестве базы данных, кеша, брокера сообщений и механизма потоковой передачи. В Redis реализованы такие структуры данных как [строки](https://redis.io/docs/data-types/strings/), [хэши](https://redis.io/docs/data-types/hashes/), [списки](https://redis.io/docs/data-types/lists/), [наборы](https://redis.io/docs/data-types/sets/), [отсортированные наборы](https://redis.io/docs/data-types/sorted-sets/) с возможностью ограничения по диапазону, [битовые карты](https://redis.io/docs/data-types/bitmaps/), [hyperloglogs](https://redis.io/docs/data-types/hyperloglogs/), [геопространственные индексы](https://redis.io/docs/data-types/geospatial/) и [потоки](https://redis.io/docs/data-types/streams/). Redis имеет встроенную поддержку [репликации](https://redis.io/docs/management/replication/), [Lua сценариев](https://redis.io/commands/eval/), [алгоритмов кэширования](https://redis.io/docs/reference/eviction/), [транзакций](https://redis.io/docs/manual/transactions/) и различных режимов [сохранения на диск](https://redis.io/docs/management/persistence/), а также обеспечивает высокую доступность с помощью [Redis Sentinel](https://redis.io/docs/management/sentinel/) и автоматическое масштабирование с помощью [Redis Cluster](https://redis.io/docs/management/scaling/).

Полезные ссылки:

* [Redis site](https://redis.io/)
* [Redis in 100 Seconds](https://www.youtube.com/watch?v=G1rOthIU-uo)

#### используя Memcached

Memcached — это универсальная распределенная система кэширования в памяти. Он часто используется для ускорения динамических веб-сайтов, управляемых базами данных, путем кэширования данных и объектов в ОЗУ, чтобы уменьшить количество запросов к внешнему источнику данных (например, базу данных или API). Memcached — это бесплатное программное обеспечение с открытым исходным кодом, распространяемое под лицензией Revised BSD. Memcached можно запустить в Unix-подобных операционных системах (Linux и macOS) и в Microsoft Windows. Система требует наличия в ОС библиотеки `libevent`.

API-интерфейсы Memcached предоставляют доступ к очень большой хеш-таблице, распределенной по нескольким машинам. Когда таблица заполнена, последующие вставки приводят к удалению старых данных, которые дольше всего не запрашивались (LRU). Приложения, использующие Memcached, обычно пытаются найти данные, требуемые для выполнения входящих запросов, в оперативной памяти, а в случае неудачи переходят к использованию
более медленного резервного хранилища, такого как база данных.

Memcached не имеет внутреннего механизма для отслеживания промахов кэша, которые могут произойти. Однако некоторые сторонние утилиты предоставляют эту функциональность.

Полезные ссылки:

* [Memcached](https://memcached.org/)
* [Википедия](https://ru.wikipedia.org/wiki/Memcached)
* [Memcached, From Official Github](https://github.com/memcached/memcached#readme)
* [Memcached Tutorial](https://www.tutorialspoint.com/memcached/index.htm)

### Кэш на клиентском уровне

Кэширование на стороне клиента — это хранение сетевых данных в локальном кеше для повторного использования в будущем. После того, как приложение получает сетевые данные, оно сохраняет этот ресурс в локальном кэше. После кэширования ресурса браузер использует кэш при будущих запросах этого ресурса для повышения производительности.

Полезные ссылки:

* [Кэш на клиентском уровне](https://tproger.ru/translations/cache-levels-on-the-web/)
* [Everything you need to know about HTTP Caching](https://www.youtube.com/watch?v=HiBDZgTNpXY)

### Кэш на уровне приложения

Кэширование на уровне приложения сокращает время выполнения определённых операций. В качестве примера можно привести комплексные вычисления, запросы данных к другим сервисам или общие данные, используемые в одинаковых запросах.

Полезные ссылки:

* [Кэш на уровне приложения](https://tproger.ru/translations/cache-levels-on-the-web/)

## Безопасность в сети

Безопасность в сети относится к защитным мерам, принимаемым разработчиками для защиты веб-приложений от угроз, которые могут повлиять на его работу.

Полезные ссылки:

* [Why HTTPS Matters](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https)
* [Википедия – OWASP](https://ru.wikipedia.org/wiki/OWASP)
* [OWASP Web Application Security Testing Checklist](https://github.com/0xRadi/OWASP-Web-Checklist)
* [OWASP Top 10 Security Risks](https://sucuri.net/guides/owasp-top-10-security-vulnerabilities-2021/)
* [OWASP Cheatsheets](https://cheatsheetseries.owasp.org/cheatsheets/AJAX_Security_Cheat_Sheet.html)
* [Content Security Policy (CSP)](https://developer.mozilla.org/ru/docs/Web/HTTP/CSP)

### Алгоритмы хеширования

Хеш-функция – функция, осуществляющая преобразование массива входных данных произвольной длины в выходную битовую строку фиксированной 
длины, выполняемое определённым алгоритмом. Преобразование, производимое хеш-функцией, называется хешированием. Основная идея используемых в данном случае функций — применение детерминированного алгоритма. Речь идет об алгоритмическом процессе, выдающем уникальный и предопределенный результат при получении входных данных. То есть при приеме одних и тех же входных данных будет создаваться та же самая строка фиксированной длины (использование одинакового ввода каждый раз приводит к одинаковому результату). Детерминизм — важное свойство этого алгоритма. И если во входных данных изменить хотя бы один символ, будет создан совершенно другой хеш.

Полезные ссылки:

* [Hashing Algorithms](https://blog.jscrambler.com/hashing-algorithms)

#### MD5 и почему его не нужно использовать

MD5 (Message-Digest Algorithm 5) — это хеш-функция, которую в настоящее время не рекомендуется использовать из-за большого количества уязвимостей, связанных с ней. Она по-прежнему используется в качестве контрольной суммы для проверки целостности данных.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/MD5)
* [Шифрование в MD5 больше не безопасно: интерактивный тест на реальный взлом вашего пароля](https://tproger.ru/articles/md5-hacking/)
* [What is MD5?](https://www.techtarget.com/searchsecurity/definition/MD5)
* [Why is MD5 not safe?](https://infosecscout.com/why-md5-is-not-safe/)

#### Семейство криптографических алгоритмов SHA

SHA (Secure Hash Algorithms, алгоритмы криптографического хеширования) — это семейство криптографических хэш-функций, созданных Национальным институтом стандартов и технологий (NIST). В семейство входят:

* SHA-0: опубликован в 1993 году, это первый алгоритм в семействе. Вскоре после публикации его использование было прекращено из-за нераскрытого существенного недостатка.
* SHA-1: создан для замены SHA-0 и напоминает MD5, этот алгоритм считается небезопасным с 2010 года.
* SHA-2: это не алгоритм, а набор алгоритмов, наиболее популярными из которых являются SHA-256 и SHA-512. SHA-2 по-прежнему безопасен и широко используется.
* SHA-3: создан благодаря конкурсу на новую хеш-функцию, организованный Национальным институтом стандартов и технологий. Новейший член семейства. SHA-3 наиболее безопасен и не имеет тех же конструктивных недостатков, что и его собратья.

Полезные ссылки:

* [Википедия – SHA](https://ru.wikipedia.org/wiki/SHA)
* [Википедия – SHA-1](https://ru.wikipedia.org/wiki/SHA-1)
* [Википедия – SHA-2](https://ru.wikipedia.org/wiki/SHA-2)
* [Википедия – SHA-3](https://ru.wikipedia.org/wiki/SHA-3)

#### scrypt

scrypt — это функция хэширования паролей (похожая на bcrypt). Разрабатывалась с целью усложнить аппаратные реализации путём увеличения количества ресурсов, требуемых для вычисления. Это затрудняет атаки методом полного перебора или «грубой силы». Scrypt в основном используется в качестве алгоритма доказательства выполненной работы (proof-of-work) в криптовалютах.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/Scrypt)

#### bcrypt

bcrypt — это функция хеширования паролей, которая доказала свою надежность и безопасность с момента её публикации в 1999 году. Она была реализована во всех наиболее часто используемых языках программирования.

Полезные ссылки:

* [Википедия](https://ru.wikipedia.org/wiki/Bcrypt)
* [bcrypts npm package](https://www.npmjs.com/package/bcrypt)
* [Understanding bcrypt](https://auth0.com/blog/hashing-in-action-understanding-bcrypt/)
* [bcrypt explained](https://www.youtube.com/watch?v=O6cmuiTBZVs)

### Рекомендации по защите API

Полезные ссылки:

* [API Security Best Practices](https://roadmap.sh/best-practices/api-security)
* [Рекомендации по защите API](https://github.com/MaksimDzhangirov/PHP-roadmap/blob/master/api-security.md)

#### HTTPS

HTTPS — это безопасный способ передачи данных между веб-сервером и браузером.

Связь через HTTPS начинается с этапа рукопожатия, во время которой сервер и клиент договариваются о том, как шифровать связь, в частности, они выбирают алгоритм шифрования и секретный ключ. После рукопожатия вся связь между сервером и клиентом будет зашифрована с использованием согласованного алгоритма и ключа.

На этапе рукопожатия используется особый тип криптографии, называемый асимметричной криптографией, для безопасной связи, даже если клиент и сервер ещё не согласовали секретный ключ. После фазы рукопожатия связь HTTPS шифруется с помощью симметричной криптографии, которая намного эффективнее, но требует, чтобы и клиент, и сервер знали секретный ключ.

Полезные ссылки:

* [Почему протокол HTTPS так важен](https://web.dev/why-https-matters/)
* [What is HTTPS?](https://www.cloudflare.com/en-gb/learning/ssl/what-is-https/)
* [Why HTTPS Matters](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https)
* [Enabling HTTPS on Your Servers](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/enable-https)
* [How HTTPS works (comic)](https://howhttps.works/)
* [SSL, TLS, HTTP, HTTPS Explained](https://www.youtube.com/watch?v=hExRDVZHhig)
* [HTTPS — Stories from the field](https://www.youtube.com/watch?v=GoXgl9r0Kjk)
* [HTTPS explained with carrier pigeons](https://baida.dev/articles/https-explained-with-carrier-pigeons)

#### Content Security Policy

Content Security Policy (CSP, политика защиты контента) — это стандарт компьютерной безопасности, введенный для предотвращения межсайтового скриптинга, кликджекинга и других атак путем внедрения кода, возникающих в результате выполнения вредоносного содержимого на веб-странице, которой доверяет пользователь.

Полезные ссылки:

* [Content Security Policy (CSP)](https://developer.mozilla.org/ru/docs/Web/HTTP/CSP)
* [Google Devs — Content Security Policy (CSP)](https://developers.google.com/web/fundamentals/security/csp)

#### Cross-Origin Resource Sharing

Cross-Origin Resource Sharing (CORS, «совместное использование ресурсов между разными источниками») — это механизм, основанный на HTTP-заголовке, который позволяет серверу указывать любые источники (домен, схему или порт), кроме своего собственного, из которых браузер должен разрешать загрузку ресурсов.

Полезные ссылки:

* [Cross-Origin Resource Sharing (CORS)](https://developer.mozilla.org/ru/docs/Web/HTTP/CORS)
* [Cross-Origin Resource Sharing](https://ru.wikipedia.org/wiki/Cross-origin_resource_sharing)
* [CORS in 100 Seconds](https://www.youtube.com/watch?v=4KHiSt0oLJ0)
* [CORS in 6 minutes](https://www.youtube.com/watch?v=PNtFSVU-YTI)

#### SSL/TLS

Secure Sockets Layer (SSL, «слой защищённых сокетов») и Transport Layer Security (TLS, «протокол защиты транспортного уровня») — это криптографические протоколы, используемые для обеспечения безопасности интернет-коммуникаций. Эти протоколы шифруют данные, которые передаются через Интернет, поэтому любой, кто попытается перехватить пакеты, не сможет их интерпретировать. Одно из отличий, которое важно знать, заключается в том, что SSL в настоящее время признан устаревшим из-за проблем с безопасностью, и большинство современных веб-браузеров больше не поддерживают его. Но TLS по-прежнему безопасен и широко поддерживается, поэтому желательно использовать TLS.

Полезные ссылки:

* [Подробное описание SSL/TLS и его криптографической системы](https://github.com/MaksimDzhangirov/complete-gRPC/blob/main/SSL_TLS_lecture_rus.md)
* [Википедия – SSL/TLS](https://ru.wikipedia.org/wiki/TLS)
* [Cloudflare – What is SSL?](https://www.cloudflare.com/learning/ssl/what-is-ssl/)

#### 10 главных угроз безопасности веб-приложений от OWASP

Периодически OWASP составляет список TOP-10 самых распространенных векторов атак на современные веб-приложения.

Полезные ссылки:

* [10 главных угроз безопасности веб-приложений от OWASP](https://owasp.org/www-project-top-ten/)
* [OWASP Топ 10 2021 на русском](https://2sharp.pro/infosec/92-owasp-top-10-2021.html)

#### Виды атак:
* [CSRF](https://ru.wikipedia.org/wiki/%D0%9C%D0%B5%D0%B6%D1%81%D0%B0%D0%B9%D1%82%D0%BE%D0%B2%D0%B0%D1%8F_%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D0%BB%D0%BA%D0%B0_%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D0%B0)
* [XSS](https://ru.wikipedia.org/wiki/%D0%9C%D0%B5%D0%B6%D1%81%D0%B0%D0%B9%D1%82%D0%BE%D0%B2%D1%8B%D0%B9_%D1%81%D0%BA%D1%80%D0%B8%D0%BF%D1%82%D0%B8%D0%BD%D0%B3)
* [семантика URL](https://thomasvilhena.com/2021/04/protecting-against-semantic-attacks)
* [SQL инъекции](https://ru.wikipedia.org/wiki/%D0%92%D0%BD%D0%B5%D0%B4%D1%80%D0%B5%D0%BD%D0%B8%D0%B5_SQL-%D0%BA%D0%BE%D0%B4%D0%B0)

#### Как обезопасить сервер

Изучите материалы, связанные с безопасностью вашего сервера и о том, как его защитить. Вот о чём следует позаботиться в первую очередь:

* Используйте брандмауэр. Один из самых эффективных способов защитить сервер — использовать брандмауэр для блокировки всего ненужного входящего трафика. Для этого вы можете использовать `iptables` в Linux системах или аппаратный брандмауэр.
* Закройте ненужные порты: обязательно закройте все порты, которые не нужны для правильной работы вашего сервера. Это уменьшит число возможных направлений атак на ваш сервер и затруднит получение злоумышленниками доступа.
* Используйте надежные пароли. Используйте длинные и сложные пароли для всех своих учетных записей и рассмотрите возможность использования диспетчера паролей для их безопасного хранения.
* Поддерживайте свою систему в актуальном состоянии. Обязательно обновляйте операционную систему и программное обеспечение, используя свежие патчи для исправления ошибок безопасности. Это поможет предотвратить использование уязвимостей злоумышленниками.
* Используйте SSL/TLS для передачи информации: используйте Secure Sockets Layer (SSL) или Transport Layer Security (TLS) для шифрования информации между вашим сервером и клиентскими устройствами. Это поможет защититься от атак типа «злоумышленник посередине» (man-in-the-middle attack) и других типов киберугроз.
* Используйте систему обнаружения несанкционированного проникновения (IDS): IDS отслеживает сетевой трафик и предупреждает вас о любых подозрительных действиях, что может помочь вам своевременно выявлять потенциальные угрозы и реагировать на них.
* Включите двухфакторную аутентификацию. Двухфакторная аутентификация добавляет дополнительный уровень безопасности вашим учетным записям, требуя второй формы аутентификации, такой как код, отправленный на ваш телефон, в дополнение к вашему паролю.

Также узнайте об OpenSSL, о создании собственной PKI, а также об управлении сертификатами, обновлениями и взаимной аутентификацией клиентов с помощью сертификатов x509.

## Тестирование

Ключом к созданию программного обеспечения, отвечающего требованиям и не имеющего недочётов, является тестирование. Тестирование программного обеспечения помогает разработчикам понять, что они создают правильное программное обеспечение. Когда тесты запускаются как часть процесса разработки (часто с использованием инструментов непрерывной интеграции), они укрепляют доверие к написанному коду и предотвращают ухудшения качества кода.

Полезные ссылки:

* [What is Software Testing?](https://www.guru99.com/software-testing-introduction-importance.html)
* [Testing Pyramid](https://www.browserstack.com/guide/testing-pyramid-for-test-automation)

### Unit-тестирование

Unit тестирование — это тестирование отдельных составляющих (модулей, функций/методов, подпрограмм и т. д.) программного обеспечения, чтобы убедиться в правильности их работы. Это низкоуровневое тестирование обеспечивает функциональную надежность небольших компонентов и снимает нагрузку с высокоуровневых тестов. Как правило, разработчик пишет эти тесты в процессе разработки, и они выполняются как автоматизированные тесты.

Полезные ссылки:

* [Википедия – Unit-тестирование](https://ru.wikipedia.org/wiki/%D0%9C%D0%BE%D0%B4%D1%83%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
* [Unit Testing Tutorial](https://www.guru99.com/unit-testing-guide.html)
* [What is Unit Testing?](https://youtu.be/3kzHmaeozDI)

### Интеграционное тестирование

К интеграционному тестированию относится обширная категория тестов, в которых несколько программных модулей интегрируются и тестируются как группа. Оно предназначено для проверки взаимодействия между несколькими сервисами, ресурсами или модулями. Например, взаимодействие API с бэкенд сервисом или сервиса с базой данных.

Полезные ссылки:

* [Википедия – Интеграционное тестирование](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%BE%D0%B5_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
* [Integration Testing](https://www.guru99.com/integration-testing.html)
* [How to Integrate and Test Your Tech Stack](https://thenewstack.io/how-to-integrate-and-test-your-tech-stack/)
* [What is Integration Testing?](https://youtu.be/QYCaaNz8emY)

### Функциональное тестирование

Функциональное тестирование — это проверка программного обеспечения на соответствие функциональным требованиям. Обычно это разновидность тестирования методом «чёрного ящика», при которой тестер не понимает исходный код; тестирование выполняется путем предоставления входных данных и сравнения ожидаемых/фактических результатов. Ему притипоставляется нефункциональное тестирование, которое включает тестирование производительности, нагрузки, масштабируемости и несанкционированного проникновения.

Полезные ссылки:

* [Функциональное тестирование](https://ru.wikipedia.org/wiki/%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
* [Non-functional testing](https://en.wikipedia.org/wiki/Non-functional_testing)
* [What is Functional Testing?](https://www.guru99.com/functional-testing.html)
* [Functional Testing vs Non-Functional Testing](https://youtu.be/j_79AXkG4PY)

## CI/CD
### Определение

CI/CD (непрерывная интеграция/непрерывное доставка) — это практика автоматизации сборки, тестирования и развертывания приложений с основной целью раннего обнаружения проблем и более быстрого выпуска релизов в продакшен.

Полезные ссылки:

* [CI/CD](https://ru.wikipedia.org/wiki/CI/CD)
* [DevOps CI/CD Explained in 100 Seconds by Fireship](https://www.youtube.com/watch?v=scEDHsr3APg)
* [Automate your Workflows with GitHub Actions](https://www.youtube.com/watch?v=nyKZTKQS_EQ)
* [What is CI/CD?](https://about.gitlab.com/topics/ci-cd/)
* [A Primer: Continuous Integration and Continuous Delivery (CI/CD)](https://thenewstack.io/a-primer-continuous-integration-and-continuous-delivery-ci-cd/)
* [3 Ways to Use Automation in CI/CD Pipelines](https://thenewstack.io/3-ways-to-use-automation-in-ci-cd-pipelines/)
* [Articles about CI/CD](https://thenewstack.io/category/ci-cd/)

### CI – Непрерывная интеграция

Непрерывная интеграция – это практика разработки программного обеспечения, при которой разработчики регулярно объединяют изменения программного кода в центральном репозитории, после чего автоматически выполняется сборка, тестирование и запуск. Понятие непрерывной интеграции чаще всего применяется к стадии сборки или интеграции процесса выпуска ПО и включает в себя как компонент автоматизации (например, сервис непрерывной интеграции или сборки), так и компонент культуры разработки (например, обучение частой интеграции). Главная задача непрерывной интеграции – быстрее находить и исправлять ошибки, улучшать качество ПО и сокращать временные затраты на проверку и выпуск новых обновлений ПО.

Полезные ссылки:

* [CI – Непрерывная интеграция](https://ru.wikipedia.org/wiki/%D0%9D%D0%B5%D0%BF%D1%80%D0%B5%D1%80%D1%8B%D0%B2%D0%BD%D0%B0%D1%8F_%D0%B8%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D1%8F)
* [Подробнее о непрерывной интеграции](https://aws.amazon.com/ru/devops/continuous-integration/)

### CD – Непрерывная доставка

Непрерывная доставка – это практика разработки программного обеспечения, когда при любых изменениях в программном коде выполняется автоматическая сборка, тестирование и подготовка к окончательному выпуску. Непрерывная доставка является одним из основополагающих принципов разработки современных приложений, поскольку расширяет практику непрерывной интеграции за счет того, что все изменения кода после стадии сборки развертываются в тестовой и/или в продакшен среде. При правильном внедрении у разработчиков всегда будет готовый к развертыванию собранный экземпляр ПО, прошедший стандартизированную процедуру тестирования.

Полезные ссылки:

* [CD – Непрерывная доставка](https://ru.wikipedia.org/wiki/%D0%9D%D0%B5%D0%BF%D1%80%D0%B5%D1%80%D1%8B%D0%B2%D0%BD%D0%B0%D1%8F_%D0%B4%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%BA%D0%B0)
* [Подробнее о непрерывной доставке](https://aws.amazon.com/ru/devops/continuous-delivery/)

## [Основные принципы проектирования программного обеспечения и виды архитектур приложений](https://github.com/MaksimDzhangirov/PHP-roadmap/blob/master/software-design-and-architecture.md)

## Основные принципы разработки и проектирования

В этом разделе мы обсудим некоторые основные принципы разработки и проектирования, которым необходимо следовать при создании бэкенд части любого приложения. Эти принципы обеспечат эффективность, масштабируемость и удобство сопровождения бэкенда.

**1. Разделение ответственности (SoC)**
Разделение ответственности — это фундаментальный принцип, согласно которому различные функции системы должны быть максимально независимыми. Этот подход улучшает 	удобство сопровождения и масштабируемость, позволяя разработчикам работать над отдельными компонентами, не влияя друг на друга. Разделите бэкенд на четко выраженные модули и уровни, такие как хранилище данных, бизнес-логика и сетевое взаимодействие.

**2. Повторное использование**
Повторное использование — это возможность использовать компоненты, функции или модули в нескольких местах без дублирования кода. При разработке бэкенда ищите возможности повторного использования существующего кода. Используйте такие методы, как создание вспомогательных функций, абстрактных классов и интерфейсов, чтобы повысить возможность повторного использования и уменьшить дублирование.

**3. Чем проще, тем лучше (KISS)**
Принцип KISS гласит, что чем проще система, тем легче ее понять, поддерживать и расширять. При проектировании бэкенда старайтесь максимально упростить архитектуру и код. Используйте четкие соглашения об именах и модульные структуры и избегайте чрезмерных технических усложнений и ненужной сложности.

**4. Не повторяйтесь (DRY)**
Не дублируйте код или функции в вашем бэкенде. Дублирование может привести к несогласованности и проблемам сопровождения. Вместо этого сосредоточьтесь на создании повторно используемых компонентов, функций или модулей, которые можно использовать в разных частях бэкенда.

**5. Масштабируемость**
Масштабируемая система — это система, которая может эффективно работать при увеличении числа пользователей, запросов или данных. Разрабатывая бэкенд с учетом масштабируемости, особое внимание уделите хранению данных, кэшированию, балансировке нагрузки и горизонтальному масштабированию (добавление дополнительных экземпляров бэкенд сервера).

**6. Безопасность**
О безопасности всегда следует серьёзно заботиться при разработке любого приложения. Всегда следуйте лучшим практикам для предотвращения брешей в системе безопасности, таким как защита конфиденциальных данных, использование безопасных протоколов передачи информации (например, HTTPS), внедрение механизмов аутентификации и авторизации и проверка вводимых пользователем данных.

**7. Тестирование**
Тестирование имеет решающее значение для обеспечения надежности и стабильной работы бэкенда. Внедрите комплексную стратегию тестирования, включающую unit тесты, интеграционные тесты и тесты производительности. Используйте инструменты автоматизированного тестирования и настройте конвейеры непрерывной интеграции (CI) и непрерывного развертывания (CD), чтобы упростить процесс тестирования и развертывания.

**8. Документация**
Надлежащая документация помогает разработчикам понимать и поддерживать кодовую базу бэкенда. Напишите четкую и краткую документацию для своего кода, объясняющую цель, функциональность и способы его использования. Кроме того, используйте комментарии и принятые соглашения об именах, чтобы сделать сам код более читабельным и не требующим пояснений.

Следуя этим принципам разработки и проектирования, вы сможете создать эффективный, безопасный и удобный в сопровождении бэкенд для своих приложений.

Полезные ссылки:

* [DesignPatternsPHP](https://designpatternsphp.readthedocs.io/ru/latest/README.html)
* [Паттерны проектирования](https://refactoring.guru/ru/design-patterns)
* [Основные принципы проектирования программного обеспечения и виды архитектур приложений](https://github.com/MaksimDzhangirov/PHP-roadmap/blob/master/software-design-and-architecture.md)

### Шаблоны проектирования

Шаблоны проектирования — это типичные решения часто встречающихся проблем при проектировании программного обеспечения. Их можно разделить на три категории:

* Порождающие шаблоны для создания объектов
* Структурные шаблоны, обеспечивающие взаимосвязь между объектами
* Поведенческие шаблоны, помогающие определить, как объекты взаимодействуют

Полезные ссылки:

* [Design Patterns for Humans](https://github.com/kamranahmedse/design-patterns-for-humans)
* [GOF design patterns](https://springframework.guru/gang-of-four-design-patterns/)

----------------------------------------------------------------------------------------------------------------------------

* [Порождающие шаблоны проектирования](https://designpatternsphp.readthedocs.io/ru/latest/Creational/README.html)
  * 1.1 [Абстрактная фабрика (Abstract Factory)](https://designpatternsphp.readthedocs.io/ru/latest/Creational/AbstractFactory/README.html#abstract-factory)
  * 1.2 [Строитель (Builder)](https://designpatternsphp.readthedocs.io/ru/latest/Creational/Builder/README.html#builder)
  * 1.3 [Фабричный Метод (Factory Method)](https://designpatternsphp.readthedocs.io/ru/latest/Creational/FactoryMethod/README.html#factory-method)
  * 1.4 [Объектный пул (Pool)](https://designpatternsphp.readthedocs.io/ru/latest/Creational/Pool/README.html#pool)
  * 1.5 [Прототип (Prototype)](https://designpatternsphp.readthedocs.io/ru/latest/Creational/Prototype/README.html#prototype)
  * 1.6 [Простая Фабрика (Simple Factory)](https://designpatternsphp.readthedocs.io/ru/latest/Creational/SimpleFactory/README.html#simple-factory)
  * 1.7 [Синглтон (Singleton)](https://github.com/MaksimDzhangirov/PHP-cheatsheet/blob/master/singleton.md)
  * 1.8 [Статическая Фабрика (Static Factory)](https://designpatternsphp.readthedocs.io/ru/latest/Creational/StaticFactory/README.html#static-factory)
* [Структурные шаблоны проектирования](https://designpatternsphp.readthedocs.io/ru/latest/Structural/README.html)
  * 2.1 [Адаптер (Adapter/Wrapper)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Adapter/README.html#adapter-wrapper)
  * 2.2 [Мост (Bridge)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Bridge/README.html#bridge)
  * 2.3 [Компоновщик (Composite)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Composite/README.html#composite)
  * 2.4 [Преобразователь Данных (Data Mapper)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/DataMapper/README.html#data-mapper)
  * 2.5 [Декоратор (Decorator)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Decorator/README.html#decorator)
  * 2.6 [Внедрение Зависимости (Dependency Injection)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/DependencyInjection/README.html#dependency-injection)
  * 2.7 [Фасад (Facade)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Facade/README.html#facade)
  * 2.8 [Текучий Интерфейс (Fluent Interface)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/FluentInterface/README.html#fluent-interface)
  * 2.9 [Приспособленец (Flyweight)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Flyweight/README.html#flyweight)
  * 2.10 [Прокси (Proxy)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Proxy/README.html#proxy)
  * 2.11 [Реестр (Registry)](https://designpatternsphp.readthedocs.io/ru/latest/Structural/Registry/README.html#registry)  
* [Поведенческие шаблоны проектирования](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/README.html)
  * 3.1 [Цепочка Обязанностей (Chain Of Responsibilities)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/ChainOfResponsibilities/README.html#chain-of-responsibilities)
  * 3.2 [Команда (Command)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Command/README.html#command)
  * 3.3 [Итератор (Iterator)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Iterator/README.html)
  * 3.4 [Посредник (Mediator)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Mediator/README.html#mediator)
  * 3.5 [Хранитель (Memento)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Memento/README.html#memento)
  * 3.6 [Объект Null (Null Object)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/NullObject/README.html#null-object)
  * 3.7 [Наблюдатель (Observer)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Observer/README.html#observer)
  * 3.8 [Спецификация (Specification)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Specification/README.html#specification)
  * 3.9 [Состояние (State)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/State/README.html#state)
  * 3.10 [Стратегия (Strategy)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Strategy/README.html#strategy)
  * 3.11 [Шаблонный Метод (Template Method)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/TemplateMethod/README.html#template-method)
  * 3.12 [Посетитель (Visitor)](https://designpatternsphp.readthedocs.io/ru/latest/Behavioral/Visitor/README.html#visitor)
 * 4 [Локатор Служб (Service Locator)](https://designpatternsphp.readthedocs.io/ru/latest/More/ServiceLocator/README.html#service-locator)
 * 5 [Хранилище (Repository)](https://designpatternsphp.readthedocs.io/ru/latest/More/Repository/README.html#repository)
 * 6 [Сущность-Атрибут-Значение (Entity–Attribute–Value)](https://designpatternsphp.readthedocs.io/ru/latest/More/EAV/README.html#entity-attribute-value-eav)

1. Гамма Э., Хелм Р., Джонсон Р., Влиссидес Дж. Паттерны объектно-ориентированного проектирования. – СПб.: Питер, 2020. – 448 с.: ил.
2. Фаулер, Мартин. Шаблоны корпоративных приложений.: Пер. с англ. – М.: ООО "И. Д. Вильямс", 2016. – 544 с.: ил. – Парал. тит. англ.
3. Мэтт Зандстра. PHP 8: объекты, шаблоны и методики программирования, 6-е издание, 2021.

### Предметно-ориентированное проектирование

Предметно-ориентированное проектирование (DDD) — это подход к разработке программного обеспечения, направленный на моделирование программного обеспечения в соответствии с предметной областью, основываясь на мнении экспертов в этой области.

С точки зрения объектно-ориентированного программирования это означает, что структура и язык программного кода (имена классов, методы классов, переменные классов) должны соответствовать предметной области. Например, если программное обеспечение обрабатывает запросы на кредитование, оно может иметь такие классы, как LoanApplication («Запрос на кредитование») и Customer («Клиент»), и такие методы, как AcceptOffer («Одобрить запрос») и Withdraw («Отказать в запросе»).

DDD связывает реализацию с эволюционирующейся моделью и преследует следующие цели:

* Сосредоточение внимания проекта на смысловом ядре (core domain) и логике предметной области;
* Заложение в основую сложных проектов модели предметной области;
* Инициирование творческого сотрудничества между техническими экспертами и экспертами в предметной области для итеративной доработки концептуальной модели, направленной на решение конкретных проблем предметной области.

Полезные ссылки:

* [Предметно-ориентированное проектирование](https://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%B5%D0%B4%D0%BC%D0%B5%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
* [Domain Driven Design Quickly](https://matfrs2.github.io/RS2/predavanja/literatura/Avram%20A,%20Marinescu%20F.%20-%20Domain%20Driven%20Design%20Quickly.pdf)

---------------------------------------------------------------------------------------------------------------------------

1. Betts Thomas (ed.), Domain-Driven Design in Practice, NY: InfoQ, 2018. – 36 p.
2. Boyle M. Domain-Driven Design with Golang: Use Golang to create simple, maintainable systems to solve complex business problems, Birmingham: Packt Publishing, 2022. — 203 p.
3. Brent Roose, LARAVEL BEYOND CRUD, 2020.
4. Buenosvinos Carlos, Soronellas Christian, Akbary Keyvan. Domain-Driven Design in PHP, Packt Publishing, 2017. – 394 p.
5. Chandrasekaran P., Krishnan K. Domain-Driven Design with Java – A Practitioner's Guide, Packt, 2022. – 302 p.
6. DDD Europe, Domain-Driven Design: The First 15 Years, Leanpub.com, 2020. – 294 p.
7. Griffin Jesse, Domain-Driven Laravel: Learn to Implement Domain-Driven Design Using Laravel, Apress Media LLC., 2020. — 621 p.
8. Joo Martin. Domain-Driven Design with Laravel, Gumroad, 2022. – 259 р.
9. Khononov Vlad Learning Domain-Driven Design: Aligning Software Architecture and Business Strategy, O’Reilly Media, Inc., 2021. — 340 p.
10. Kumar A. Domain Driven Design with Spring Boot: Enterprise Application from scratch, 2018. — 268 p.
11. Nair Vijay. Practical Domain-Driven Design in Enterprise Java: Using Jakarta EE, Eclipse MicroProfile, Spring Boot, and the Axon Framework, Apress, 2019. – 387 p.
12. Percival H.J.W. et al. Architecture Patterns with Python Enabling Test-Driven Development, Domain-Driven Design, and Event-Driven Microservices, O'Reilly, 2020. – 292 p.
13. Эванс Эрик. Предметно-ориентированное проектирование (DDD): структуризация сложных программных систем.: Пер. с англ. М.: ООО "И. Д. Вильямс", 2011. – 448 с.: ил. – Парал. тит. англ. 
14. Вервов Вон. Предметно-ориентированное проектирование: самое основное.:Пер. с англ. – СпВ.: ООО "Альфа-книга". 2017. – 160 с.: ил. – Парал. тит. англ.
15. Вернов Вон. Реализация методов предметно-ориентированного проектирования.: Пер. с англ. – М.: ООО "И.Д. Вильямс", 2016. – 688 с.: ил. – Парал. тит. англ.
16. Миллетт Скотт, Тьюн Ник. Предметно-ориентированное проектирование: Паттерны, принципы и методы, СПб.: Питер, 2017. — 832 с.: ил.
17. [Пример приложения с использованием DDD, Event Sourcing и CQRS на Symfony](https://github.com/jorge07/symfony-5-es-cqrs-boilerplate)

### Разработка через тестирование

Разработка через тестирование (TDD) — это процесс написания тестов на основе требований к программному обеспечению, которые не будут успешно пройдены до тех пор, пока не будет разработано программное обеспечение для удовлетворения этих требований. После прохождения этих тестов цикл повторяется для рефакторинга кода или разработки других функциональных возможностей/требований. Теоретически это гарантирует, что программное обеспечение будет написано с учетом требований наиболее простым из возможных способов и позволит избежать ошибок в коде.

Полезные ссылки:

* [Разработка через тестирование](https://ru.wikipedia.org/wiki/%D0%A0%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0_%D1%87%D0%B5%D1%80%D0%B5%D0%B7_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)

#### SOLID

SOLID — это аббревиатура пяти основных принципов проектирования в объектно‑ориентированном программировании — принцип единой ответственности, открытости/закрытости, подстановки Барбары Лисков, разделения интерфейсов и инверсии зависимостей.

Аббревиатура SOLID была предложена Робертом Мартином, автором нескольких книг, широко известных в сообществе разработчиков. Эти принципы позволяют строить на базе ООП масштабируемые и сопровождаемые программные продукты с понятной бизнес‑логикой.

Полезные ссылки:

* [SOLID](https://ru.wikipedia.org/wiki/SOLID_(%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5))
* [SOLID принципы в PHP](https://dev.to/evrtrabajo/solid-in-php-d8e)
* [SOLID — принципы объектно‑ориентированного программирования](https://web-creator.ru/articles/solid)

#### [KISS](https://ru.wikipedia.org/wiki/KISS_(%D0%BF%D1%80%D0%B8%D0%BD%D1%86%D0%B8%D0%BF))

Большая часть программных систем необосновано перегружена практически ненужными функциями, что ухудшает удобство их использование конечными пользователями, а также усложняет их поддержку и развитие разработчиками. Следование принципу «KISS» позволяет разрабатывать решения, которые просты в использовании и в сопровождении.

KISS («Чем проще, тем лучше») — это принцип проектирования и программирования, при котором простота системы декларируется в качестве основной цели или ценности. Есть два варианта расшифровки аббревиатуры: «**K**eep **I**t **S**imple, **S**tupid» и более корректный «**K**eep **I**t **S**hort and **S**imple».

Также KISS имеет много общего c принципом разделения интерфейсов из пяти принципов SOLID, сформулированных Робертом Мартином.

Полезные ссылки:

* [Принцип программирования KISS — делайте вещи проще](https://web-creator.ru/articles/kiss)

#### [YAGNI](https://ru.wikipedia.org/wiki/YAGNI)

Следование данному принципу заключается в том, что возможности, которые не описаны в требованиях к системе, просто не должны реализовываться. Это позволяет вести разработку, руководствуясь экономическими критериями — заказчик не должен оплачивать ненужные ему функции, а разработчики не должны тратить своё оплачиваемое время на реализацию того, что не требуется.

Основная проблема, которую решает принцип YAGNI (**Y**ou **A**in’t **G**onna **N**eed **I**t, «Вам это никогда не понадобится») — это устранение тяги программистов к излишней абстракции, к экспериментам «из интереса» и к реализации функционала, который сейчас не нужен, но, по мнению разработчика, может либо вскоре понадобиться, либо просто будет полезен, хотя в реальности такого очень часто не происходит.

Любые «бонусные» возможности усложняют сопровождение, увеличивают вероятность ошибок и усложняют взаимодействие с продуктом, — между объёмом кодовой базы и описанными характеристиками есть прямая зависимость. Больше написанного кода — труднее сопровождать и выше вероятность появления «багов».

Полезные ссылки:

* [Принцип программирования YAGNI — «Вам это не понадобится»](https://web-creator.ru/articles/yagni)

#### [DRY](https://ru.wikipedia.org/wiki/Don%E2%80%99t_repeat_yourself)

Следование принципу программирования «DRY» (**D**on’t **R**epeat **Y**ourself, «Не повторяйтесь») позволяет добиться высокой сопровождаемости проекта, простоты внесения изменений и качественного тестирования.

Если код не дублируется, то для изменения логики достаточно внесения исправлений всего в одном месте и проще тестировать одну (пусть и более сложную) функцию, а не набор из десятков однотипных. Следование принципу DRY всегда приводит к декомпозиции сложных алгоритмов на простые функции. А декомпозиция сложных операций на более простые (и повторно используемые) значительно упрощает понимание программного кода. Повторное использование функций, вынесенных из сложных алгоритмов, позволяет сократить время разработки и тестирования новой функциональности.

Полезные ссылки:

* [Принцип программирования DRY — don’t repeat yourself / не повторяйте себя](https://web-creator.ru/articles/dry)

### CQRS

CQRS или разделение ответственности на команды и запросы, определяет архитектурный шаблон, в котором основное внимание уделяется разделению подходов к операциям чтения и записи для хранилища данных. CQRS также можно использовать вместе с шаблоном Event Sourcing для сохранения состояния приложения в виде упорядоченной последовательности событий, что позволяет восстанавливать данные на любой момент времени.

Полезные ссылки:

* [CQRS](https://martinfowler.com/bliki/CQRS.html)
* [CQRS Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)

### Генерация событий (Источники событий, Event Sourcing)

Генерация событий, источники событий — это шаблон проектирования, в котором состояние системы представляется в виде последовательности событий, произошедших во времени. В системе с источником событий изменения состояния системы записываются как события и сохраняются в хранилище событий. Текущее состояние системы определяется путем воспроизведения событий из хранилища событий.

Одним из основных преимуществ источника событий является то, что он обеспечивает четкую и проверяемую историю всех изменений, которые произошли в системе. Это может быть полезно для отладки и отслеживания эволюции системы с течением времени.

Источники событий часто используются в сочетании с другими шаблонами, такими как разделение ответственности на команды и запросы (CQRS) и предметно-ориентированное проектирование, для создания масштабируемых и быстро реагирующих систем со сложной бизнес-логикой. Их также стоит использовать для создания систем, которые должны поддерживать функциональную возможность отмены/возврата или которые должны интегрироваться с внешними системами.

Полезные ссылки:

* [Генерация событий](https://martinfowler.com/eaaDev/EventSourcing.html)

## Виды архитектур приложений

Архитектурный шаблон — это обобщённое, повторно используемое решение часто встречающейся проблемы в архитектуре программного обеспечения в заданном контексте. Архитектурные шаблоны решают различные проблемы разработки программного обеспечения, такие как ограничения производительности компьютерного оборудования, высокая степень доступности и минимизация бизнес-рисков.

### Монолитная архитектура

Монолитная архитектура — это шаблон, в котором приложение обрабатывает запросы, реализует бизнес-логику, взаимодействует с базой данных и создает HTML для фронтенда. Проще говоря, это одно приложение, которое отвечает за выполнение нескольких задач. Его внутренние компоненты сильно связаны и развернуты как единое целое.

Полезные ссылки:

* [Монолитная архитектура. Традиционный метод разработки приложений](https://codernet.ru/articles/drugoe/monolitnaya_arxitektura_tradiczionnyij_metod_razrabotki_prilozhenij/)
* [Pattern: Monolithic Architecture](https://microservices.io/patterns/monolithic.html)
* [Monolithic Architecture – Advantages & Disadvantages](https://datamify.medium.com/monolithic-architecture-advantages-and-disadvantages-e71a603eec89)

### Микросервисная архитектура

Микросервисная архитектура — это шаблон, в котором сильно связные, слабо связанные сервисы разрабатываются, обслуживаются и развертываются отдельно. Каждый компонент отвечает отдельную задачу, а в сочетании приложение выполняет общую бизнес-функцию.

Полезные ссылки:

* [Microservices Guide](https://martinfowler.com/microservices/)
* [Pattern: Microservice Architecture](https://microservices.io/patterns/microservices.html)
* [What is Microservices?](https://smartbear.com/solutions/microservices/)
* [Microservices 101](https://thenewstack.io/microservices-101/)
* [Primer: Microservices Explained](https://thenewstack.io/primer-microservices-explained/)
* [Articles about Microservices](https://thenewstack.io/category/microservices/)

-------------------------------------------------------------------------------------------------------------------------

1. Bellemare A. Building Event-Driven Microservices: Leveraging Organizational Data at Scale, O’Reilly Media, 2020. – 324 p.
2. Betts N. Microservices vs. Monoliths – The Reality Beyond the Hype, NY: InfoQ, 2017. – 65 p.
3. Boner J. Reactive Microservices Architecture, O'Reilly Media, Inc., 2016. – 54 p.
4. Bruce Morgan, Pereira Paulo. Microservices in Action, Manning Publications, 2019. — 395 p.
5. Cambell Edward. Microservices Architecture, 2015. — 98 p.
6. Carneiro Cloves, Schmelmer Tim. Microservices From Day One. Build robust and scalable software from the start, Apress, 2017. — 258 p.
7. Davis Ashley. Bootstrapping Microservices with Docker, Kubernetes, and Terraform: A project-based guide, Manning Publications, 2021. — 442 p.
8. Fowler Susan J. Production-Ready Microservices, O'Reilly, 2017. — 316 p.
9. Garofolo Ethan. Practical Microservices: Build Event-Driven Architectures with Event Sourcing and CQRS, Pragmatic Bookshelf, 2020. — 292 p.
10. Hunter II Thomas. Advanced Microservices: A Hands-on Approach to Microservice Infrastructure and Tooling, Apress, 2017. — 181 p.
11. Indrasiri Kasun, Siriwardena Prabath. Microservices for the Enterprise: Designing, Developing, and Deploying, Apress, 2019. — 422 p.
12. Meghan K.M. Microservices: Quick Book: A practical guide with examples using Spring Boot, Cloud Config, Cloud Bus, Cloud Security, Eureka, Hystrix, Axon with CQRS and Event Sourcing, Independently published, 2021. — 137 p.
13. Mitra Ronnie, Nadareishvili Irakli. Microservices: Up and Running: A Step-by-Step Guide to Building a Microservice Architecture, O’Reilly Media, 2021. — 255 p.
14. Murugesan Vikram, Microservices Deployment Cookbook, Packt Publishing, 2017. — 305 p.
15. Nadareishvili Irakli, Mitra Ronnie, McLarty Matt, Amundsen Mike. Microservice Architecture: Aligning Principles, Practices, and Culture, O'Reilly, 2016. — 146 p.
16. Newman Sam, Building Microservices, Designing Fine-Grained Systems, 2nd Edition. — O’Reilly Media, 2021. — 615 p.
17. Ньюмен С. Создание микросервисов. — СПб.: Питер, 2016. — 304 с.: ил.
18. Newman Sam, Monolith to Microservices, Evolutionary Patterns to Transform Your Monolith, O’Reilly Media, 2020. — 300 p.
19. Ньюмен С. От монолита к микросервисам: Эволюционные шаблоны для трансформации монолитной системы, Пер. с англ. — СПб.: БЧВ-Петербург, 2021 — 272 с.: ил.
20. Osman Paul, Microservices Development Cookbook: Design and build independently deployable, modular services, Packt Publishing, 2018. — 260 p.
21. Parminder Singh Kocher. Microservices and Containers, Addison-Wesley Professional, 2018. — 304 p.
22. Peralta J.H. Microservice APIs: Using Python, Flask, FastAPI, OpenAPI and more, Manning, 2023. — 411 p.
23. Peralta Jose Haro. Microservice APIs: With examples in Python, Manning Publications Co., 2022. — 425 p.
24. Richards M. Microservices vs. Service-Oriented Architecture, O’Reilly Media, 2016. — 55 p.
25. Richards Mark. Microservices AntiPatterns and Pitfalls, O'Reilly, 2016. — 66 p.
26. Richardson Chris. Microservices Patterns: With examples in Java, Manning Publications, 2019. — 520 p.
27. Ричардсон Крис Микросервисы. Паттерны разработки и рефакторинга. — СПб.: Питер, 2019. — 544 с.: ил.
28. Richardson Chris. Microservices. From Design to Deployment, San Francisco: NGINX, Inc., 2016 — 80 p.
29. Rocha Hugo Filipe Oliveira. Practical Event-Driven Microservices Architecture, Apress Media LLC, 2022. — 457 p.
30. Rodger Richard. The Tao of Microservices, Manning Publications, 2018. — 328 p.
31. Sharma Rahul, Mathur Akshay. Traefik API Gateway for Microservices: With Java and Python Microservices Deployed in Kubernetes, Apress Media LLC., 2020. — 269 p.
32. Sharma Sourabh, RV Rajesh, Gonzalez David. Microservices: Building Scalable Software, Packt Publishing, 2017. — 919 p.
33. Sharma U.R. Practical Microservices: Take advantage of microservices capabilities to build a flexible and efficient system with Java, Packt Publishing, 2017. – 307 p.
34. Siriwardena Prabath, Dias Nuwan. Microservices Security in Action, Manning, 2020. — 512 p.
35. Stetson Chris. Microservices Reference Architecture, NGINX Inc., 2017. — 58 p.
36. Surianarayanan Chellammal. Essentials of Microservices Architecture: Paradigms, Applications, and Techniques, Taylor & Francis Group, LLC., 2020. — 314 p.
37. Thomas Betts (ed.) Microservices – Patterns and Practices, NY: InfoQ, 2020. — 42 p.
38. Umesh Ram Sharma. Srivastava Anubhava. Practical Microservices, Packt Publishing, 2017. — 254 p.
39. Vinicius Feitosa Pacheco, Microservice Patterns and Best Practices: Explore patterns like CQRS and event sourcing to create scalable, maintainable, and testable microservices, 2018.
40. Wolff Eberhard. Microservices: A Practical Guide: Principles, Concepts, and Recipes, 2nd Edition. — CreateSpace Independent Publishing Platform, 2020. — 319 p.
41. Wolff Eberhard. Microservices: Flexible Software Architecture, Addison-Wesley, 2016. — 432 p.
42. Wrba Guillermo. Designing and Building Solid Microservice Ecosystems, 2021. — 631 p.
43. Yanaga E. Migrating to Microservice Databases, O’Reilly Media, 2017.
44. Zeev Avidan, Hans Otharsson. Accelerating the Digital Journey from Legacy Systems to Modern Microservices, OpenLegacy, 2018. — 98 p. 
45. [Пример микросервисной архитектуры](https://github.com/GoogleCloudPlatform/microservices-demo)
46. [microservices.io](https://microservices.io/)

### Сервис-ориентированная архитектура (SOA)

SOA или сервис-ориентированная архитектура, определяет способ повторного использования программных компонентов с помощью интерфейсов сервисов. Эти интерфейсы используют общепринятые стандарты передачи информации таким образом, что их можно быстро добавлять в новые приложения без необходимости каждый раз выполнять глубокую интеграцию.

Полезные ссылки:

* [Сервис-ориентированная архитектура (SOA)](https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D1%80%D0%B2%D0%B8%D1%81-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%B0%D1%8F_%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0)
* [Reference Architecture Foundation for Service Oriented Architecture](http://docs.oasis-open.org/soa-rm/soa-ra/v1.0/soa-ra.html)

### Serverless-архитектура

Бессерверная архитектура — это архитектура, в которой разработчик создает и запускает приложения без необходимости арендовать/покупать серверы или управлять ими. При облачных вычислениях/бессерверных технологиях серверы существуют, но управляются поставщиком облачных услуг. Ресурсы используются по мере необходимости, по запросу и часто с использованием автоматического масштабирования.

Полезные ссылки:

* [Serverless Architectures](https://martinfowler.com/articles/serverless.html)
* [Serverless](https://www.ibm.com/cloud/learn/serverless)
* [AWS Services](https://aws.amazon.com/serverless/)
* [Serverless Computing in 100 Seconds](https://www.youtube.com/watch?v=W_VV2Fx32_Y&ab_channel=Fireship)

### Service Mesh

Service mesh — это сеть микросервисов, соединенных с помощью взаимосвязанных интеллектуальных прокси-серверов. Она используется для управления и защиты связи между микросервисами и предоставляет такие функции, как балансировка нагрузки, обнаружение сервисов и наблюдаемость.

В service mesh каждый микросервис обычно представляет собой экземпляр легковесного прозрачного прокси-сервера, называемого "envoy" («посланником»). Посланники управляют взаимодействием между микросервисами и предоставляют такие функции, как балансировка нагрузки, маршрутизация и безопасность.

Service mesh обычно реализуются с использованием шаблона sidecar, в котором посланники развертываются вместе с микросервисами, за которые они несут ответственность. Это позволяет отделить service mesh от микросервисов и упрощает управление и обновление.

Service mesh обычно используются в облачных архитектурах и часто управляются с помощью панели управления, которая отвечает за настройку и управление посланниками. Некоторыми популярными реализациями service mesh являются Istio и Linkerd.

Полезные ссылки:

* [What is a Service Mesh?](https://www.nginx.com/blog/what-is-a-service-mesh/)

### Twelve-Factor Apps («12-факторное приложение»)

«12-факторное приложение» — это методология создания масштабируемых и удобных в сопровождении приложений «программное обеспечение как услуга» (SaaS). Она основана на наборе лучших практик, которые авторы методологии определили как необходимые для создания современных облачных приложений.

Методология «12-факторного приложения» состоит из следующих принципов:

* Кодовая база: для приложения должна быть единая кодовая база с несколькими сценариями развертывания.
* Зависимости: приложение должно явно объявлять и изолировать свои зависимости.
* Конфигурация: приложение должно хранить конфигурацию в среде выполнения.
* Сторонние службы (Backing services): приложение должно рассматривать сторонние службы (backing services) как подключаемые ресурсы.
* Сборка, релиз, выполнение: стадии сборки, релиза и выполнения должны быть изолированы.
* Процессы: приложение должно выполняться как один или несколько процессов не сохраняющих внутреннее состояние (stateless).
* Привязка портов (Port binding): приложение должно предоставлять доступ к своим службам через привязку порта.
* Параллелизм: приложение должно масштабироваться за счет добавления дополнительных процессов, а не за счет добавления потоков.
* Утилизируемость (Disposability): приложение должно быть спроектировано таким образом, чтобы его можно было быстро запускать и останавливать.
* Паритет разработки/работы приложения: среды локальной разработки, промежуточного развёртывания (staging) и рабочего развёртывания (production) должны быть максимально похожими.
* Логи: приложение должно работать с логами как с потоками событий.
* Задачи администрирования: приложение должно запускать задачи администрирования/обслуживания как разовые процессы.

Методология «12-факторного приложения» широко используется разработчиками SaaS приложений и считается передовой практикой для создания облачных приложений, которые являются масштабируемыми, удобными в обслуживании и простыми в развертывании.

Полезные ссылки:

* [The Twelve-Factor App. Принципы архитектуры современных веб-приложений](https://www.asyncink.com/twelve-factors)
* [The Twelve-Factor App](https://12factor.net/)

### Гексагональная архитектура

Гексагональная архитектура (Hexagonal Architecture, также известна как архитектура портов и адаптеров), разработанная Алистером Кокберном и описана Стивом Фриманом и Натом Прайсом в книге "Growing Object Oriented Software with Tests".

Гексагональная архитектура — это архитектурный шаблон, направленный на создание слабо связанных компонентов приложений. Компоненты подключаются к программной среде с помощью портов и адаптеров. Слабая связанность позволяет реализовать ещё одно преимущество — взаимозаменяемость компонент.

Полезные ссылки:

* [Hexagonal architecture: an example of implementation](https://oumarkonate.com/hexagonal-architecture-an-example-of-implementation/)

### Чистая архитектура

Чистая архитектура — это рекомендации по организации системной архитектуры. Они были предложены Робертом С. Мартином и основаны на ряде прежних архитектурных построений, таких как гексагональная архитектура, луковая архитектура и т. д.

Это одно из основных правил для создания программного обеспечения (ПО), удобного в тестировании и поддержке.

Полезные ссылки:

* [Get Your Hands Dirty on Clean Architecture](https://www.packtpub.com/product/get-your-hands-dirty-on-clean-architecture/9781839211966)

-------------------------------------------------------------------------------------------------------------------------

1. Software Architecture: The Hard Parts: Modern Trade-Off Analyses for Distributed Architectures 1st Edition by Neal Ford, Mark Richards, Pramod Sadalage, Zhamak Dehghani, 2021.
2. Fundamentals of Software Architecture: An Engineering Approach 1st Edition by Mark Richards, Neal Ford, 2020.
3. Фаулер М. Рефакторинг: улучшение существующего кода. – Пер. с англ. – СПб: Символ-Плюс, 2003. – 432 с, ил.
4. Роберт Мартин, Чистый код: создание, анализ и рефакторинг. Библиотека программиста, 2019.
5. Роберт Мартин, Чистая архитектура. Искусство разработки программного обеспечения. – СПб.: Питер, 2018. – 352 с.: ил.
6. [martinfowler.com](https://martinfowler.com/)

## Поисковые системы

Поисковые системы являются неотъемлемой частью любого веб-приложения, ответственного за предоставление пользователям эффективных и релевантных результатов поиска. Они хранят и извлекают данные на основе уникальных индексов, которые обеспечивают быстрый и точный поиск. Для бэкэнд-разработчика крайне важно понимать функциональные возможности поисковых систем и способы их интеграции в ваше веб-приложение.

### Типы поисковых систем

Существует два основных типа поисковых систем:

1. **Полнотекстовые поисковые системы**: они специально разработаны для поиска и анализа текстовых документов. Они могут эффективно индексировать большие объемы текста и предоставлять релевантные результаты на основе ключевых слов или фраз. Примерами популярных полнотекстовых поисковых систем являются **Elasticsearch**, **Solr** и **Amazon CloudSearch**.

2. **Поисковый механизм баз данных**: механизмы поиска в базах данных являются встроенными функциональными возможностями большинства баз данных. Они обеспечивают поиск в данных, хранящихся в базе данных. Примерами могут быть **FULLTEXT поиск MySQL** и **Full-Text поиск PostgreSQL**.

### Ключевые идеи

При работе с поисковыми системами важно понимать следующие ключевые идеи:

**Индексирование**: процесс анализа и хранения данных в оптимизированном формате для быстрого поиска и извлечения.
**Токенизация**: разбиение текста на отдельные слова или термины (также называемые токенами) для эффективного индексирования и поиска.
**Запрос**: действие по поиску проиндексированных данных путем задания определенного вопроса или запроса информации на основе ключевых слов или фраз.
**Оценка релевантности**: оценка, присваиваемая каждому результату поиска, которая показывает, насколько близко он соответствует запросу, на основе алгоритмов и моделей релевантности.

### Интеграция

Чтобы интегрировать поисковую систему в ваше веб-приложение, вы обычно выполняете следующие шаги:

**Выбераете поисковую систему**: определите поисковую систему, которая лучше всего соответствует потребностям вашего приложения, учитывая такие факторы, как масштабируемость, производительность и простота интеграции.
**Индексируйте свои данные**: анализируйте и сохраняйте свои данные с помощью выбранной поисковой системы. Этот процесс может включать создание индекса, указание полей и определение того, как данные должны быть токенизированы и проанализированы.
**Реализуйте функции поиска**: разработайте бекэнд код для обработки поисковых запросов, т. е. для отправки запросов в поисковую систему и анализа ответов. Кроме того, обязательно обрабатывайте вводимые пользователем данные, такие как ключевые слова, фразы и фильтры.
**Отображение результатов поиска**. Разработайте фронтэнд вашего приложения, чтобы отображать результаты поиска в удобном для пользователя виде, включая разбиение на страницы, сортировку и фильтрацию.

Полезные ссылки:

* [Поисковая система](https://ru.wikipedia.org/wiki/%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%D0%BE%D0%B2%D0%B0%D1%8F_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0)
* [Поисковая машина](https://ru.wikipedia.org/wiki/%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%D0%BE%D0%B2%D0%B0%D1%8F_%D0%BC%D0%B0%D1%88%D0%B8%D0%BD%D0%B0)

### Elasticsearch

Elasticsearch по своей сути является документоориентированной поисковой системой. Это документоориентированная база данных, которая позволяет вам ВСТАВЛЯТЬ, УДАЛИТЬ, ПОЛУЧАТЬ (INSERT, DELETE , RETRIEVE) и даже выполнять аналитику сохраненных записей. Но Elasticsearch отличается от любой другой базы данных общего назначения, с которой вы работали ранее. По сути, это поисковая система, предлагающая целый арсенал функций, которые вы можете использовать для извлечения хранящихся в ней данных в соответствии с вашими критериями поиска. И при этом очень быстро.

Полезные ссылки:

* [Elasticsearch Website](https://www.elastic.co/elasticsearch/)
* [Elasticsearch Documentation](https://www.elastic.co/guide/index.html)
* [Elasticsearch – Википедия](https://ru.wikipedia.org/wiki/Elasticsearch)

### [Solr](https://ru.wikipedia.org/wiki/Solr)

Solr обладает высокой надежностью, масштабируемостью и отказоустойчивостью, обеспечивая распределенное индексирование, репликацию и запросы с балансировкой нагрузки, автоматическое переключение при отказе и восстановление, централизованную настройку и многое другое. Solr отвечает за функции поиска и навигации многих крупнейших интернет-сайтов мира.

Полезные ссылки:

* [Official Website](https://solr.apache.org/)
* [Official Documentation](https://solr.apache.org/resources.html#documentation)
* [Solr – Википедия](https://ru.wikipedia.org/wiki/Solr)

## Брокеры сообщений

Брокеры сообщений — это технология передачи информации между приложениями, помогающая создать стандартный механизм интеграции для поддержки облачных, микросервисных, бессерверных и гибридных облачных архитектур. Двумя самыми известными брокерами сообщений являются `RabbitMQ` и `Apache Kafka`.

Полезные ссылки:

* [Брокер сообщений](https://ru.wikipedia.org/wiki/%D0%91%D1%80%D0%BE%D0%BA%D0%B5%D1%80_%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D0%BD%D0%B8%D0%B9)
* [Introduction to Message Brokers](https://www.youtube.com/watch?v=57Qr9tk6Uxc)

### [RabbitMQ](https://ru.wikipedia.org/wiki/RabbitMQ)

С десятками тысяч пользователей RabbitMQ является одним из самых популярных брокеров сообщений с открытым исходным кодом. RabbitMQ легковесен и прост в развертывании локально и в облаке. Он поддерживает несколько протоколов обмена сообщениями. RabbitMQ можно развернуть в распределенных и федеративных конфигурациях для удовлетворения требований касающихся масштабирования и высокой доступности.

Полезные ссылки:

* [RabbitMQ – Википедия](https://ru.wikipedia.org/wiki/RabbitMQ)
* [RabbitMQ Tutorials](https://www.rabbitmq.com/getstarted.html)
* [RabbitMQ Tutorial – Message Queues and Distributed Systems](https://www.youtube.com/watch?v=nFxjaVmFj5E)

### [Kafka](https://ru.wikipedia.org/wiki/Apache_Kafka)

Apache Kafka – это распределенная платформа потоковой передачи событий с открытым исходным кодом, используемая тысячами компаний для высокопроизводительных конвейеров данных, потоковой аналитики, интеграции данных и критически важных приложений.

Полезные ссылки:

* [Apache Kafka – Википедия](https://ru.wikipedia.org/wiki/Apache_Kafka)
* [Apache Kafka quickstart](https://kafka.apache.org/quickstart)
* [Apache Kafka Fundamentals](https://www.youtube.com/watch?v=B5j3uNBH8X4)

## Контейнеризация или виртуализация

Контейнеры и виртуальные машины — два самых популярных подхода к настройке программной инфраструктуры для вашей организации.

Полезные ссылки:

* [Containerization vs. Virtualization: Everything you need to know](https://middleware.io/blog/containerization-vs-virtualization/)
* [Containerization or Virtualization – The Differences](https://www.youtube.com/watch?v=1WnDHitznGY)

### Kubernetes

Kubernetes — это платформа управления контейнерами [с открытым исходным кодом](https://github.com/kubernetes/kubernetes) и доминирующий продукт в этой сфере. Используя Kubernetes, команды могут развертывать образы на нескольких базовых хостах, определяя их желаемую доступность, логику развертывания и масштабирования с помощью YAML. Kubernetes был создан на основе Borg, внутренней платформы Google, используемой для предоставления и распределения вычислительных ресурсов (аналогично системам Autopilot и Aquaman Microsoft Azure).

Популярность Kubernetes сделала его одним из наиболее важных навыков для DevOps инженера и послужила толчком к созданию команд разработчиков для платформы во всей отрасли. Эти команды разработчиков для платформ часто существуют с единственной целью сделать Kubernetes доступным и удобным для использования их коллегами, занимающихся разработкой продуктов.

Полезные ссылки:

* [Kubernetes Website](https://kubernetes.io/)
* [Kubernetes Documentation](https://kubernetes.io/docs/home/)
* [Kubernetes Crash Course for Absolute Beginners](https://www.youtube.com/watch?v=s_o8dwzRlu4)
* [Primer: How Kubernetes Came to Be, What It Is, and Why You Should Care](https://thenewstack.io/primer-how-kubernetes-came-to-be-what-it-is-and-why-you-should-care/)
* [Kubernetes: An Overview](https://thenewstack.io/kubernetes-an-overview/)

### Docker

Docker — это платформа для работы с контейнерными приложениями. Среди его функций — фоновый системный процесс и клиент для управления контейнерами и взаимодействия с ними, реестры для хранения образов и приложение для настольного ПК, объединяющее все эти функции.

Полезные ссылки:

* [Docker — Википедия](https://ru.wikipedia.org/wiki/Docker)
* [Docker Documentation](https://docs.docker.com/)
* [What is Docker | AWS](https://aws.amazon.com/docker/)
* [Complete Docker Course – From BEGINNER to PRO!](https://www.youtube.com/watch?v=RqTEHSBrYFw)
* [Docker Tutorial](https://youtu.be/3c-iBn73dDE)
* [Docker simplified in 55 seconds](https://youtu.be/vP_4DlOH1G4)
* [Дорожная карта для изучения Docker](https://github.com/MaksimDzhangirov/PHP-roadmap/blob/master/docker-roadmap.md)

### [rkt](https://ru.bmstu.wiki/Rocket_(rkt))

Rocket (rkt) — является альтернативой Docker, разработанной компанией CoreOS с прицелом на соответствие строгим требованиям к безопасности и производительности.

Полезные ссылки:

* [rkt — Википедия](https://ru.bmstu.wiki/Rocket_(rkt))
* [What is Rkt (Rocket) container technology? Should you use it?](https://bobcares.com/blog/rkt-rocket-container-technology-use/)
* [Docker vs Rkt (Rocket) – Which one to choose?](https://bobcares.com/blog/docker-vs-rkt-rocket/)

### [LXC](https://ru.wikipedia.org/wiki/LXC)

LXC — это аббревиатура, используемая для Linux контейнеров, которые представляют собой операционную систему, используемую для запуска нескольких систем Linux виртуально на контролируемом хосте через одно ядро ​​Linux. LXC — это интерфейс пользовательского пространства для функций ограничений ядра Linux. Благодаря мощному API и простым инструментам пользователи Linux могут легко создавать системные контейнеры или контейнеры приложений и управлять ими.

Полезные ссылки:

* [LXC — Википедия](https://ru.wikipedia.org/wiki/LXC)
* [LXC Documentation](https://linuxcontainers.org/lxc/documentation/)
* [What is LXC?](https://linuxcontainers.org/lxc/introduction/)
* [Linux Container (LXC) Introduction](https://youtu.be/_KnmRdK69qM)
* [Getting started with LXC containers](https://youtu.be/CWmkSj_B-wo)

## GraphQL

GraphQL — это язык запросов для API-интерфейсов и среда, в которой они выполняются. GraphQL позволяет детально и понятно описать данные в вашем API, даёт клиентам возможность запрашивать именно то, что им нужно, упрощает развитие API с течением времени и предоставляет мощные инструменты разработчика.

Полезные ссылки:

* [GraphQL](https://en.wikipedia.org/wiki/GraphQL)
* [Introduction to GraphQL](https://graphql.org/learn/)
* [The Fullstack Tutorial for GraphQL](https://www.howtographql.com/)
* [GraphQL Tutorials](https://odyssey.apollographql.com/)
* [GraphQL Course for Beginners](https://www.youtube.com/watch?v=ed8SzALpx1Q)

### Apollo

Apollo — это платформа для построения унифицированного графа, коммуникационного слоя, который помогает вам управлять потоком данных между вашими клиентами (такими как веб-приложения и нативные приложения) и бекэнд сервисами.

Полезные ссылки:

* [Apollo Website](https://www.apollographql.com/)
* [Official Docs](https://www.apollographql.com/docs/)
* [Official YouTube Channel](https://www.youtube.com/c/ApolloGraphQL/)
* [GraphQL With React Tutorial – Apollo Client](https://www.youtube.com/watch?v=YyUWW04HwKY)

### Relay Modern

Relay — это JavaScript клиент, используемый в браузере для получения GraphQL данных. Это JavaScript среда, разработанная Facebook для управления и получения данных в React приложениях. Он создан с учетом масштабируемости для поддержки сложных приложений, таких как Facebook. Основная цель GraphQL и Relay — обеспечить мгновенное реакцию пользовательского интерфейса на действия пользователя.

Полезные ссылки:

* [Official Website](https://relay.dev/)
* [Introduction to Relay modern](https://relay.dev/docs/)

## Вебсокеты

Веб-сокеты представляют собой двустороннюю связь между серверами и клиентами, т. е. обе стороны взаимодействуют друг с другом и обмениваются данными одновременно. Этот протокол определяет полнодуплексную связь с нуля. Веб-сокеты на ещё один шаг приближают веб-браузеры к приложениям для настольного компьютера, предоставляя им богатые функциональные возможности.

Полезные ссылки:

* [WebSocket — Википедия](https://ru.wikipedia.org/wiki/WebSocket)
* [Пример использования](https://learn.javascript.ru/websocket)
* [Introduction to WebSockets](https://www.tutorialspoint.com/websockets/index.htm)
* [A Beginners Guide to WebSockets](https://www.youtube.com/watch?v=8ARodQ4Wlf4)
* [Socket.io Library Bidirectional and low-latency communication for every platform](https://socket.io/)

## Server Sent Events

Server-Sent Events (SSE) – это технология, которая позволяет веб-серверу передавать данные клиенту в режиме реального времени. Она использует HTTP-соединение для отправки потока данных с сервера клиенту, и клиент может отслеживать эти события и предпринимать действия при их получении.

SSE полезен для приложений, требующих обновлений в режиме реального времени, таких как системы чатов, бегущие строки акций и каналы социальных сетей. Это простой и эффективный способ установить долговременное соединение между клиентом и сервером и он поддерживается большинством современных веб-браузеров.

Чтобы использовать SSE, клиент должен создать объект EventSource и указать URL-адрес скрипта на стороне сервера, который будет отправлять события. Затем сервер может отправлять события, записывая их в поток ответов, при этом соблюдая определенное форматирование.

Полезные ссылки:

* [Server-sent events – Википедия](https://ru.wikipedia.org/wiki/Server-sent_events)
* [Server-Sent Events – MDN](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)

## Вебсерверы

Веб-серверы могут быть аппаратными, программными или комбинированными.

### Аппаратные

Аппаратный веб-сервер — это компьютер, на котором размещено программное обеспечение веб-сервера и файлы, формирующие веб-сайт (например, HTML-документы, изображения, таблицы стилей CSS и файлы JavaScript). Веб-сервер устанавливает соединение с Интернетом и осуществляет физический обмен данными с другими устройствами, подключенными к сети.

### Программные

Программный веб-сервер имеет ряд программных компонентов, которые контролируют доступ онлайн-пользователей к размещенным файлам. Это как минимум HTTP-сервер. Программное обеспечение, которое имеет представление и понимает HTTP (протокол, который ваш браузер использует для просмотра веб-страниц) и URL-адреса (веб-адреса), назвается HTTP-сервером. Содержимое размещенных веб-сайтов отправляется на устройство конечного пользователя через HTTP-сервер, доступ к которому можно получить через доменные имена сайтов, которые он содержит.

По сути, HTTP-запрос выполняется браузером каждый раз, когда ему требуется файл, хранящийся на веб-сервере. Соответствующий (аппаратный) веб-сервер получает запрос, который затем принимается соответствующим (программным) HTTP-сервером, а он в свою очередь затем находит запрошенный контент и возвращает его браузеру по HTTP. Если сервер не может найти запрошенную страницу, он отвечает ошибкой 404.

Полезные ссылки:

* [Веб-сервер — Википедия](https://ru.wikipedia.org/wiki/%D0%92%D0%B5%D0%B1-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80)
* [What is a Web Server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server)
* [Web Server Concepts and Examples](https://youtu.be/9J1nJOivdyw)

### Nginx

NGINX — это мощный веб-сервер, использующий событийно-ориентированную архитектуру без потоков, которая позволяет ему превосходить в производительности Apache при правильной настройке. Он также может выполнять другие важные функции, такие как балансировка нагрузки, HTTP-кеширование или использование в качестве обратного прокси-сервера.

Полезные ссылки:

* [Nginx — Википедия](https://ru.wikipedia.org/wiki/Nginx)
* [Official Website](https://nginx.org/)
* [NGINX Explained in 100 Seconds](https://www.youtube.com/watch?v=JKxlsvZXG7c)

### Apache

Apache — это бесплатный HTTP-сервер с открытым исходным кодом, доступный во многих операционных системах, но в основном используемый в дистрибутивах Linux. Это один из самых популярных вариантов для веб-разработчиков, поскольку, по оценке W3Techs, на его долю приходится более 30% всех веб-сайтов.

Полезные ссылки:

* [Apache — Википедия](https://ru.wikipedia.org/wiki/Apache_HTTP_Server)
* [Apache Server Website](https://httpd.apache.org/)
* [What is Apache Web Server?](https://www.youtube.com/watch?v=kaaenHXO4t4)

### Caddy

Веб-сервер Caddy — это расширяемый кроссплатформенный веб-сервер с открытым исходным кодом, написанный на Go. Он обладает несколькими действительно привлекательными функциональными возможностями, такими как автоматическая поддержка SSL/HTTPs и очень простой файл конфигурации.

Полезные ссылки:

* [Caddy — Wikipedia](https://en.wikipedia.org/wiki/Caddy_(web_server))
* [Official Website](https://caddyserver.com/)
* [Getting started with Caddy the HTTPS Web Server from scratch](https://www.youtube.com/watch?v=t4naLFSlBpQ)

### MS IIS

Internet Information Services (IIS) для Windows® Server — это гибкий, безопасный и лёгкий в обращении веб-сервер для размещения чего-либо в Интернете.

Полезные ссылки:

* [MS IIS — Википедия](https://ru.wikipedia.org/wiki/Internet_Information_Services)
* [Official Website](https://www.iis.net/)
* [Learn Windows Web Server IIS](https://www.youtube.com/watch?v=1VdxPWwtISA)

## [Создание приложений с учётом масштабирования (общие темы, которые вы должны изучить и которые нужно иметь ввиду для обеспечения надежной работы приложения)](https://medium.com/@alb.botashev/how-to-design-a-highload-app-2248b9022d3e)

В общих чертах, масштабируемость — это способность системы справляться с растущей нагрузкой за счет добавления к ней ресурсов.

Программное обеспечение, разработаваемое с учетом масштабируемости, представляет собой систему, которая способна работать с более высокими рабочими нагрузками без каких-либо фундаментальных изменений в ней, но не дайте себя обмануть, в этом нет никакой магии. Достичь желаемой цели, не привлекая
дополнительных ресурсов, можно только за счёт грамотного проектирования.

Чтобы система была масштабируемой, необходимо обратить внимание на следующие моменты, а именно:

* связность
* наблюдаемость
* эволюционируемость
* инфраструктура

Существует два основных способа создания инфраструктурой масштабируемой системы: использовать локальные ресурсы или использовать все инструменты, которые может предоставить вам провайдер облачных услуг.

Основным отличием локальных и облачных ресурсов будет ГИБКОСТЬ последних. Используя облачные провайдеры вам не нужно планировать заранее сколько и каких именно аппаратных ресурсов потребуется для реализации, вы можете модернизировать свою инфраструктуру в пару кликов, а с локальными ресурсами вам потребуется определенный уровень планирования.

Смотри также:

* [Scalable Architecture: A Definition and How-To Guide](https://www.sentinelone.com/blog/scalable-architecture/)
* [Scaling Distributed Systems – Software Architecture Introduction](https://www.youtube.com/watch?v=gxfERVP18-g)

## Стратегии миграции

Стратегия миграции — это план перемещения данных из одного места в другое и важный этап любой миграции базы данных. Стратегия миграции данных должна включать план перемещения данных и действий с ними после их переноса в новое место.

Узнайте, как эффективно выполнять миграцию базы данных. В частности, многоэтапную миграция схем с нулевым временем простоя. Вместо того, чтобы вносить все изменения сразу (удалив весь старый код), делайте небольшие пошаговые изменения, чтобы старый код и новый код могли работать с базой данных одновременно. Затем удалите старый код и части схемы базы данных, которые больше не используются.

Полезные ссылки:

* [What is Data Migration Strategy?](https://theecmconsultant.com/data-migration-strategy)
* [Databases as a Challenge for Continuous Delivery](https://phauer.com/2015/databases-challenge-continuous-delivery/)

## Стратегии смягчения последствий в случае отказов (failure)

Этот раздел в основном относится к шаблонам облачного проектирования, которые помогают создавать масштабируемые решения. Ознакомьтесь с документацией Microsoft [Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) и этим видео, в котором рассказывается о [шаблонах Throttling, Retry и Circuit Breaker](https://www.youtube.com/watch?v=0HoTGgb5oFg).

### Graceful degradation

Graceful degradation — это принцип проектирования, согласно которому система должна быть спроектирована так, чтобы продолжать функционировать, даже если некоторые из её компонентов или функций недоступны. В контексте веб-разработки под graceful degradation понимается способность веб-страницы или приложения продолжать работу, даже если браузер или устройство пользователя не поддерживает определенные функции или технологии.

Graceful degradation часто используется в качестве альтернативы progressive enhancement — принципу проектирования, который гласит, что система должна быть спроектирована так, чтобы использовать преимущества передовых функций и технологий, если они доступны.

Посетите следующие ресурсы, если хотите получить больше информации:

* [Graceful degradation](https://www.farfetchtechblog.com/en/blog/post/the-art-of-failure-ii-graceful-degradation/)
* [Graceful degradation](https://github.com/mercari/production-readiness-checklist/blob/master/docs/concepts/graceful-degradation.md)
* [What is Graceful Degradation & Why Does it Matter?](https://blog.hubspot.com/website/graceful-degradation)
* [Four Considerations When Designing Systems For Graceful Degradation](https://newrelic.com/blog/best-practices/design-software-for-graceful-degradation)
* [The Art of Graceful Degradation](https://farfetchtechblog.com/en/blog/post/the-art-of-failure-ii-graceful-degradation/)

### Throttling

Throttling (регулирование нагрузки) — это шаблон проектирования, который используется для ограничения частоты, с которой может использоваться система или компонент. Он обычно используется в средах облачных вычислений для предотвращения чрезмерного использования ресурсов, таких как вычислительная мощность, пропускная способность сети или ёмкость хранилища.

Существует несколько способов реализации throttling в облачной среде:

* Ограничение скорости: это подразумевает определение максимального количества запросов, которые могут быть сделаны к системе или компоненту в течение определенного периода времени.

* Распределение ресурсов: это подразумевает выделение фиксированного количества ресурсов для системы или компонента, а затем ограничение использования этих ресурсов, если они превышены.

* «Ведро» с токенами: это подразумевает использование «ведра» токенов (маркеров) для представления доступных ресурсов, а затем позволяет «потреблять» определенное количество токенов при каждом запросе. Когда ведро пустое, дополнительные запросы отклоняются до тех пор, пока не станет доступно больше токенов.

Throttling является важным аспектом облачного проектирования, поскольку он помогает обеспечить эффективное использование ресурсов, а также стабильность и доступность системы. Он часто используется в сочетании с другими шаблонами проектирования, такими как автоматическое масштабирование и балансировка нагрузки, для обеспечения масштабируемой и отказоустойчивой облачной среды.

Полезные ссылки:

* [Web Api Security: DoS & DDoS attacks, Throttling, Scalability, WAF](https://www.linkedin.com/pulse/web-api-security-dos-ddos-attacks-throttling-waf-houssam-chmouri/)
* [Throttling – AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/serverless/patterns/throttling/)
* [Алгоритм текущего ведра](https://ru.wikipedia.org/wiki/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC_%D1%82%D0%B5%D0%BA%D1%83%D1%89%D0%B5%D0%B3%D0%BE_%D0%B2%D0%B5%D0%B4%D1%80%D0%B0)

### Backpressure

Backpressure — это шаблон проектирования, который используется для управления потоком данных через систему, особенно в ситуациях, когда скорость производства данных превышает скорость потребления данных. Он обычно используется в средах облачных вычислений для предотвращения перегрузки ресурсов и обеспечения своевременной и эффективной обработки данных.

Существует несколько способов реализации backpressure в облачной среде:

* Буферизация: это подразумевает хранение входящих данных в буфере до тех пор, пока они не будут обработаны, что позволяет системе продолжать получать данные, даже если она временно не может их обработать.

* Пакетная обработка: это подразумевает группировку входящих данных в пакеты и последовательную обработку пакетов, а не обработку каждого фрагмента данных по отдельности.

* Управление потоком: подразумевает использование таких механизмов, как сигналы управления потоком или управление путём разбиения на окна, для регулирования скорости, с которой данные передаются между системами.

Backpressure — важный аспект облачного проектирования, поскольку он помогает обеспечить эффективную обработку данных, а также стабильность и доступность системы. Он часто используется в сочетании с другими шаблонами проектирования, такими как автоматическое масштабирование и балансировка нагрузки, для обеспечения масштабируемой и отказоустойчивой облачной среды.

Полезные ссылки:

* [Back-pressure patterns in practice](https://www.zghurskyi.com/backpressure/)
* [Back Pressure](https://awesome-architecture.com/back-pressure/)
* [Backpressure – AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/serverless/patterns/backpressure/)

### Load Shedding, Load Shifting

Load Shifting (переключение нагрузки) – это шаблон проектирования, который используется для управления рабочей нагрузкой системы путем переноса нагрузки на разные компоненты или ресурсы в разное время. Он обычно используется в средах облачных вычислений для балансировки рабочей нагрузки системы и оптимизации использования ресурсов.

Существует несколько способов реализации перераспределения нагрузки в облачной среде:

* Планирование (диспетчеризация): это подразумевает составление графика выполнения задач или рабочих нагрузок в определенное время или через определенные промежутки времени.

* Балансировка нагрузки: это подразумевает распределение рабочей нагрузки системы между несколькими ресурсами, такими как серверы или контейнеры, для обеспечения сбалансированности рабочей нагрузки и эффективного использования ресурсов.

* Автоматическое масштабирование: это подразумевает автоматическую подстройку количества ресурсов, доступных системе, в зависимости от рабочей нагрузки, позволяя системе масштабироваться вверх или вниз по мере необходимости.

Load Shifting — важный аспект облачного проектирования, поскольку он помогает обеспечить эффективное использование ресурсов, а также стабильность и доступность системы. Он часто используется в сочетании с другими шаблонами проектирования, такими как throttling и backpressure, для обеспечения масштабируемой и отказоустойчивой облачной среды.

Полезные ссылки:

* [Load Shedding in Web Services](https://medium.com/helpshift-engineering/load-shedding-in-web-services-9fa8cfa1ffe4)
* [Load Shifting – AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/serverless/patterns/load-shifting/)

### Circuit Breaker

Шаблон проектирования circuit breaker (предохранитель) — это способ защитить систему от сбоев или чрезмерной нагрузки путем временной остановки определенных операций, если считается, что система находится в неисправном или перегруженном состоянии. Он обычно используется в средах облачных вычислений для предотвращения каскадных сбоев и повышения отказоустойчивости и доступности системы.

Circuit breaker имеет три состояния: замкнут, разомкнут и полуоткрыт. В замкнутом состоянии автоматический выключатель позволяет выполнять операции в обычном режиме. Если в системе возникает сбой или она перегружается, circuit breaker переходит в разомкнутое состояние, и все последующие операции немедленно останавливаются. По истечении заданного периода времени circuit breaker переходит в полуоткрытое состояние, и разрешается выполнение небольшого количества операций. Если эти операции выполнены успешно, circuit breaker возвращается в замкнутое состояние; если при их выполнении возникают сбои, circuit breaker возвращается в разомкнутое состояние.

Шаблон проектирования circuit breaker полезен для защиты системы от сбоев или чрезмерной нагрузки, поскольку позволяет временно остановить определенные операции и позволить системе восстановиться. Он часто используется в сочетании с другими шаблонами проектирования, такими как retries (повторные попытки) и fallbacks (резервные копии), для обеспечения более надежной и отказоустойчивой облачной среды.

Полезные ссылки:

* [Стратегии обработки ошибок: Circuit Breaker pattern](https://medium.com/@kirill.sereda/%D1%81%D1%82%D1%80%D0%B0%D1%82%D0%B5%D0%B3%D0%B8%D0%B8-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8-%D0%BE%D1%88%D0%B8%D0%B1%D0%BE%D0%BA-circuit-breaker-pattern-650232944e37)
* [Circuit Breaker – AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/rel_mitigate_interaction_failure_graceful_degradation.html)

-----------------------------------------------------------------------------------------------------------------------------------------

1. М. Нейгард Release it! Проектирование и дизайн ПО для тех, кому не всё равно. — СПб.: Питер, 2016. — 320 с.: ил. — (Серия «Библиотека программиста»).
2. [Reliability patterns](https://learn.microsoft.com/en-us/azure/architecture/framework/resiliency/reliability-patterns)
3. [Designing a Microservices Architecture for Failure](https://blog.risingstack.com/designing-microservices-architecture-for-failure/)
4. Клеппман М. Высоконагруженные приложения. Программирование, масштабирование, поддержка. — СПб.: Питер, 2018. — 640 с.: ил. — (Серия «Бестселлеры O’Reilly»).

## Горизонтальное или вертикальное масштабирование

Горизонтальное масштабирование — это изменение **количества** ресурсов. Например, увеличение количества виртуальных машин, обрабатывающих сообщения в очереди. Вертикальное масштабирование — это изменение **размера/мощности** ресурса. Например, увеличение памяти или дискового пространства, доступного машине. Масштабирование может применяться к базам данных, облачным ресурсам и другим областям вычислений.

Полезные ссылки:

* [Масштабируемость](https://ru.wikipedia.org/wiki/%D0%9C%D0%B0%D1%81%D1%88%D1%82%D0%B0%D0%B1%D0%B8%D1%80%D1%83%D0%B5%D0%BC%D0%BE%D1%81%D1%82%D1%8C)
* [Horizontal vs Vertical Scaling](https://touchstonesecurity.com/horizontal-vs-vertical-scaling-what-you-need-to-know/)
* [Scaling In Databases](https://www.geeksforgeeks.org/horizontal-and-vertical-scaling-in-databases/)
* [System Design Basics: Horizontal vs. Vertical Scaling](https://youtu.be/xpDnVSmNFX0)
* [System Design 101](https://www.youtube.com/watch?v=Y-Gl4HEyeUQ)

## [Создание приложения с учётом наблюдаемости (логирование метрик и других наблюдаемых параметров, которые могут помочь вам в отладке и решении проблем, когда что-то идет не так)](https://newrelic.com/blog/best-practices/observability-instrumentation)

В области разработки программного обеспечения наблюдаемость — это мера понимания того насколько хорошо работает система и как сделать её лучше.

Что же делает систему «наблюдаемой»? Её способность создавать и собирать метрики, логи и трассировки, чтобы мы могли понять, что происходит под капотом, и быстрее выявлять проблемы и узкие места. Вы можете реализовать все эти функции самостоятельно, но существуют программы, которые могут помочь вам в этом, например [Datadog](https://docs.datadoghq.com/), [Sentry](https://docs.sentry.io/) и [CloudWatch](https://aws.amazon.com/cloudwatch/getting-started/).

Полезные ссылки:

* [DataDog Docs](https://docs.datadoghq.com/)
* [AWS CloudWatch Docs](https://aws.amazon.com/cloudwatch/getting-started/)
* [Sentry Docs](https://docs.sentry.io/)
* [AWS re:Invent 2017: Improving Microservice and Serverless Observability with Monitor](https://www.youtube.com/watch?v=Wx0SHRb2xcI)
* [Observability and Instrumentation: What They Are and Why They Matter](https://newrelic.com/blog/best-practices/observability-instrumentation)

## Инструментирование, мониторинг, телеметрия

Под инструментированием понимают измерение производительности продукта для диагностирования ошибок и записи информации, позволяющей отслеживать причины их возникновения. Инструментирование может быть двух типов: на основе исходного кода и на основе двоичного кода.

Мониторинг бэкэнда позволяет пользователю просматривать производительность инфраструктуры, то есть компонентов, которые запускают веб-приложение. К ним относятся HTTP-сервер, промежуточное ПО, база данных, сторонние службы API и многое другое.

Телеметрия — это процесс непрерывного сбора данных из разных компонентов приложения. Эти данные помогают командам инженеров устранять неполадки в сервисах и выявлять первопричины. Другими словами, данные телеметрии обеспечивают наблюдаемость для ваших распределенных приложений.

Ссылки на ресурсы:

* [What is Instrumentation?](https://en.wikipedia.org/wiki/Instrumentation_(computer_programming))
* [What is Monitoring?](https://www.yottaa.com/performance-monitoring-backend-vs-front-end-solutions/)
* [What is Telemetry?](https://www.sumologic.com/insight/what-is-telemetry/)

## Обратите внимание также на [дорожную карту DevOps-а](https://roadmap.sh/devops)

## Часто задаваемые вопросы

### Что такое Backend-разработка

Backend-веб-разработка — это часть веб-разработки, которая касается серверной части веб-приложения. Она включает в себя создание и управление логикой на стороне сервера, подключение приложения к базе данных, создание API на стороне сервера, аутентификацию и авторизацию пользователей, а также обработку запросов пользователей и ответы на них. Часто связана с использованием таких языков программирования, как Python, Java, Ruby, PHP, JavaScript (Node.js) и .NET.

Backend-разработчик отвечает за разработку серверных компонентов веб-приложения, т. е. за работу с базами данных, обработку запросов, создание серверных API-интерфейсов, которые могут использоваться Frontend разработчиками для получения данных и управления ими, обеспечивая масштабируемость систем, т. е. он должен убедиться, что Backend может обрабатывать большой объём трафика и работать, интегрируя внешние сервисы, такие как платежные шлюзы, очереди сообщений, облачные сервисы и т. д.

### Как стать Backend-разработчиком?

Если вы новичок и только приступили к обучению, вы можете начать с изучения языка Backend-программирования, например, PHP, Python, Ruby, Java, Go и т. д.
Как только вы будете знать язык на базовом или среднее уровне, изучите менеджер пакетов для этого языка, как устанавливать и использовать внешние пакеты в своих приложениях. Выучите основы какой-либо реляционной базы данных, например, PostgreSQL и узнайте, как выполнять простые CRUD операции. При желании вы также можете выбрать и изучить веб-фреймворк для выбранного вами языка. Узнайте, как создать простой RESTful API и внедрить в него простую аутентификацию/авторизацию. Изучая все вышеперечисленное, не забудьте также о Git и GitHub.

Выполнив все приведенные выше рекомендации, вы можете начать откликаться на вакансии Backend-разработчика уровня intern/junior. Кроме того, посмотрите на дорожную карту Backend-разработчика выше, чтобы получить представление о том, что вам нужно ещё изучить и увидеть, чего вам ещё не хватает. Иметь высшее образование в области, связанной с компьютерными науками или смежной, не всегда обязательно, но необходима постоянная практика, создание портфолио и активный поиск стажировок или прохождение собеседований на должность intern/junior разработчика, чтобы начать и продвинуться по карьерной лестнице в качестве бэкэнд-разработчика.

Примечание: для закрепления полученных в ходе изучения знаний, придумывайте и создавайте различные проекты. Важно постоянно учиться, чтобы улучшать свои навыки и быть готовым к быстрому развитию технологий.

### Сколько времени нужно, чтобы стать Backend-разработчиком?

Время, необходимое для того, чтобы стать Backend-разработчиком, может варьироваться в зависимости от нескольких факторов, таких как темп вашего обучения, предыдущий опыт и количеству часов в день, которые вы можете посвятить обучению.

Если у вас уже есть опыт работы, связанный с компьютерными науками или смежной области, а также опыт программирования, вы сможете относительно быстро стать Backend-разработчиком, возможно, в течение нескольких месяцев. Однако, если у вас небольшой опыт или вообще его нет, может потребоваться больше времени, чтобы развить необходимые навыки и получить опыт, необходимый для того, чтобы стать знатоком в Backend-разработке. Это может занять от 6 месяцев до 2 лет.

### Какая зарплата у Backend-разработчика?

Зарплата Backend-разработчика может варьироваться в зависимости от таких факторов, как местоположение, опыт и размер компании. Согласно данным Glassdoor, средняя базовая зарплата Backend-разработчика в США составляет около 92 000 долларов в год. Однако она может сильно отличаться в зависимости от местоположения: в самых высокооплачиваемых городах, таких как Сан-Франциско, Сиэтл и Нью-Йорк, средняя зарплата составляет от 120 000 до 135 000 долларов в год.

Стоит иметь в виду, что это всего лишь средние значения, и заработная плата может сильно различаться в зависимости от таких факторов, как уровень опыта, конкретные навыки и компания, в которой вы работаете. С большим опытом и конкретными навыками, относящимися к работе, на которую вы претендуете, вы можете рассчитывать на больший заработок.

Стоит изучить статьи, посвященные статистике изменения зарплат за последние годы, публикуемые на сайтах для поиска работы, чтобы получить общее представление о текущем состоянии рынка в вашей области в зависимости от уровня опыта. Также попробуйте связаться с опытными специалистами Backend-разработки и получить представление об их опыте работы и диапазонах заработной платы.

### Должен ли я выучить всё, что указано в дорожной карте Backend-разработчика?

Эта дорожная карта содержит всё, с чем вы можете столкнуться, работая Backend-разработчиком. Вам может не понадобиться всё, что перечислено здесь, чтобы начать работать в отрасли; каждая работа уникальна, и чаще всего потребуется подмножество элементов дорожной карты. Однако знать свои слабые стороны тоже важно, поэтому вы можете использовать эту дорожную карту, чтобы получить представление о том, чего вам не хватает.

Если вы новичок и только начинаете, не пугайтесь, глядя на эту дорожную карту, а прочитайте ответ на вопрос "Как стать Backend-разработчиком?".

## Что ещё почитать
### [Чистый код на PHP](https://github.com/peter-gribanov/clean-code-php/blob/ru/README.md)
### [Алгоритмы и структуры данных](https://github.com/MaksimDzhangirov/algorithms-and-data-structures)
### Дискретная математика
* Теория множеств
* Булева алгебра
* Теория графов
