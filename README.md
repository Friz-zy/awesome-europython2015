# [europython20015](https://ep2015.europython.eu/p3/schedule/ep2015/list/)

[video](https://www.youtube.com/user/PythonItalia/videos)

## community


- [keynote its dangerous to go alone](https://ep2015.europython.eu/conference/talks/keynote-its-dangerous-to-go-alone)  
Django Girls  
http://yaypython.com/

- [How-To: Build a local Python community](https://ep2015.europython.eu/conference/talks/how-to-build-a-local-python-community)  
Хороший доклад по организации локального python сообщества.

- [EuroPython 2016: Help us build the next edition!](https://ep2015.europython.eu/conference/talks/europython-2016-help-us-build-the-next-edition)

## python


- [keynote python now and in the future](https://ep2015.europython.eu/conference/talks/keynote-python-now-and-in-the-future)  
Гвидо агитировал за python 3.5, но в dropbox используют сильно модифицированный python 2.7

- [type hints for python3.5](https://ep2015.europython.eu/conference/talks/type-hints-for-python-35)

- [the python compiler](https://ep2015.europython.eu/conference/talks/the-python-compiler)  
http://nuitka.net/pages/overview.html  
компиляция python в с++ вместе с libpython. Прирост скорости до 250%

- [How you can benefit from type hints](https://ep2015.europython.eu/conference/talks/how-you-can-benefit-from-type-hints)

- [Tuning Python applications can dramatically increase performance](https://ep2015.europython.eu/conference/talks/tuning-python-applications-can-dramatically-increase-performance)

- [Writing Domain Specific Languages with Python](https://ep2015.europython.eu/conference/talks/the-unabridged-guide-to-domain-specific-languages-in-python)

- [PyPy and the future of the Python ecosystem](https://ep2015.europython.eu/conference/talks/pypy-and-the-future-of-the-python-ecosystem)

- [Static type-checking is dead, long live static type-checking in Python!](https://ep2015.europython.eu/conference/talks/static-type-checking-is-dead-long-live-static-type-checking-in-python)

- [Import Deep Dive](https://ep2015.europython.eu/conference/talks/import-deep-dive)

- http://bpython-interpreter.org/  
красивый и функциональный интерфейс к стандартному интерпретатору Python для *nix.

- https://github.com/jespino/python-master-key  
MasterKey is a pure python module to open your python classes, and allow you to redefine and fix the built-in python types.
WARNING: Of course this is a Joke, don't use this module in real code!

## microservices & highload


- [nameko for microservices](https://ep2015.europython.eu/conference/talks/nameko-for-microservices)  
https://nameko.readthedocs.org/en/stable/
A microservices framework for Python that lets service developers concentrate on application logic and encourages testability.

- [stop trying to glue your services together import lymph](https://ep2015.europython.eu/conference/talks/stop-trying-to-glue-your-services-together-import-lymph)  
https://github.com/deliveryhero/lymph  
lymph is an opinionated framework for Python services. Its features are

    - Discovery: pluggable service discovery (e.g. backed by ZooKeeper)
    - RPC: request-reply messaging (via ZeroMQ + MessagePack)
    - Events: pluggable and reliable pub-sub messaging (e.g. backed by RabbitMQ)
    - Process Management


- [use python to process 12mil events per minute and still keep it simple](https://ep2015.europython.eu/conference/talks/use-python-to-process-12mil-events-per-minute-and-still-keep-it-simple)  
https://eastvisionsystems.com/projects/  
Компания занимается видое хостингом и стримингом.
Доклад об python сервисе, который парсит access.log nginx и сохраняет события в mongodb.

- [building async microservices](https://ep2015.europython.eu/conference/talks/building-async-microservices)

- [using service discovery a distributed application](https://ep2015.europython.eu/conference/talks/using-service-discovery-a-distributed-application)  
https://github.com/ultrabug?tab=repositories  
http://www.ultrabug.fr/designing-a-scalable-and-distributed-application/  
Core developer gentoo рассказывал про дизайн микросервисов с docker & consul  
https://github.com/kr/beanstalkd - Beanstalk is a simple, fast work queue

- [distributed locks with python and redis](https://ep2015.europython.eu/conference/talks/distributed-locks-with-python-and-redis)

- [python microservices on paas done right](https://ep2015.europython.eu/conference/talks/python-microservices-on-paas-done-right)

- [Arrested Development - surviving the awkward adolescence of a microservices-based application](https://ep2015.europython.eu/conference/talks/arrested-development-surviving-the-awkward-adolescence-of-a-microservices-based-application)  
Yelp деляться опытом по мигрированию на микросервисы.  
http://swagger.io/ The World's Most Popular Framework for APIs.  
https://github.com/Yelp/bravado Bravado is a python client library for Swagger 2.0 services

- [Preparing Apps for Dynamic Scaling](https://ep2015.europython.eu/conference/talks/preparing-apps-for-dynamic-scaling)  
Skyatlas рекламировал свое решение по динамическому увеличению cpu & ram в облаке как средсво для вертикального маштабирования.

- [Python for Cloud Services and Infrastructure Management](https://ep2015.europython.eu/conference/talks/python-for-cloud-services-and-infrastructure-management)

- [Python in the world of retail and mail order](https://ep2015.europython.eu/conference/talks/python-in-the-world-of-retail-and-mail-order)

## conteiners & clouds


- [keynote so i have all these docker containers now what](https://ep2015.europython.eu/conference/talks/keynote-so-i-have-all-these-docker-containers-now-what)  
Google использует docker для запуска 10000 одинаковых воркеров на свободных ресурсах датацентра  
http://kubernetes.io/

- [the lightweight cloud server war begins](https://ep2015.europython.eu/conference/talks/the-lightweight-cloud-server-war-begins)

- [to the clouds why you should deploy to the cloud even if you dont want to](https://ep2015.europython.eu/conference/talks/to-the-clouds-why-you-should-deploy-to-the-cloud-even-if-you-dont-want-to)  
Canonical рекламировал juju  
http://www.ubuntu.com/cloud/tools/juju  
https://jujucharms.com/  
Провизор: упарвляет vm, железом, ресурсами, приложениями, etc...  
Работает поверх разных технологий, в том числе Fabric & Ansible

- [architecture of a cloud hosting service using python technologies django ansible and celery](https://ep2015.europython.eu/conference/talks/architecture-of-a-cloud-hosting-service-using-python-technologies-django-ansible-and-celery)

## good code & coding & cli


- [it works on my machine writing python code for any environment](https://ep2015.europython.eu/conference/talks/it-works-on-my-machine-writing-python-code-for-any-environment)  
Разработка приложений для python 2 + 3 на примере консольной утилиты aws tools  
Python:
    * renaming: six, move wrappers to other file
    * strings: check input type
    * limitation: use backports
Os:
    * file handling: IoThread
    * file path: normalaze path with os midule
    * functionality: platform.system
Testing:
    * running: virtualenv

- [metrics driven development](https://ep2015.europython.eu/conference/talks/metrics-driven-development)

- [beyond grep practical logging and metrics](https://ep2015.europython.eu/conference/talks/beyond-grep-practical-logging-and-metrics)

- [argus the omniscient ci](https://ep2015.europython.eu/conference/talks/argus-the-omniscient-ci)

- [using git hooks to help your engineering teams work autonomously](https://ep2015.europython.eu/conference/talks/using-git-hooks-to-help-your-engineering-teams-work-autonomously)  
https://github.com/zalando/turnstile  
https://tech.zalando.com/blog/using-git-hooks-to-help-your-engineering-teams-work-autonomously-video/  
Рассказ о том, как уйти от svn в git и облегчить жизнь автономной команде инженеров.
С готовыми примерами на github.

- [python idioms to help you write good code](https://ep2015.europython.eu/conference/talks/python-idioms-to-help-you-write-good-code)

- [a deep look at logging](https://ep2015.europython.eu/conference/talks/a-deep-look-at-logging)

- [code quality in python tools and reasons](https://ep2015.europython.eu/conference/talks/code-quality-in-python-tools-and-reasons)

- [building nice command line interfaces a look beyond the stdlib](https://ep2015.europython.eu/conference/talks/building-nice-command-line-interfaces-a-look-beyond-the-stdlib)

- [come to the dark side we have a whole bunch of cookiecutters](https://ep2015.europython.eu/conference/talks/come-to-the-dark-side-we-have-a-whole-bunch-of-cookiecutters)

- [terminal whispering](https://ep2015.europython.eu/conference/talks/terminal-whispering)

- [Through the lens of Haskell: exploring new ideas for library design](https://ep2015.europython.eu/conference/talks/exploring-the-haskell-ecosystem-to-bring-back-some-ideas)

- [DumbDev -- eight rules for dumb development](https://ep2015.europython.eu/conference/talks/dumbdev-eight-rules-for-dumb-development)

- [Practical usage of advanced Python constructs](https://ep2015.europython.eu/conference/talks/practical-usage-of-advanced-python-constructs)

- [Just Because You Can, Doesn't Mean You Should](https://ep2015.europython.eu/conference/talks/just-because-you-can-doesnt-mean-you-should)

- https://pypi.python.org/pypi/hunter/  
Hunter is a flexible code tracing toolkit, not for measuring coverage, but for debugging, logging, inspection and other nefarious purposes. It has a simple Python API and a convenient terminal API (see Environment variable activation).

- https://github.com/ionelmc/python-fields  
Container class boilerplate killer

##  data mining & data storing


- [big data beautiful visualization on the browser with bokeh](https://ep2015.europython.eu/conference/talks/big-data-beautiful-visualization-on-the-browser-with-bokeh)

- [new trends in storing large data silos with python](https://ep2015.europython.eu/conference/talks/new-trends-in-storing-large-data-silos-with-python)

- [pyspark and warcraft data](https://ep2015.europython.eu/conference/talks/pyspark-and-warcraft-data)

- [scale your data not your process welcome to the blaze ecosystem](https://ep2015.europython.eu/conference/talks/scale-your-data-not-your-process-welcome-to-the-blaze-ecosystem)

- [lusterhq](https://clusterhq.com/)  
Container Data Management for your Dockerized Applications  
Господа делают решение по синхронизации данных по площадкам для контейнеров.
Используют модуль ядра zfs и пишут асинхронный код на twisted.
Пообщаться с инженерами было интересно.

- [python and postgresql a wonderful wedding](https://ep2015.europython.eu/conference/talks/python-and-postgresql-a-wonderful-wedding)

- [data-analysis-and-map-reduce-with-mongodb-and-pymongo](https://ep2015.europython.eu/conference/talks/data-analysis-and-map-reduce-with-mongodb-and-pymongo)

- [from basic distance search to a complex multi criteria search](https://ep2015.europython.eu/conference/talks/from-basic-distance-search-to-a-complex-multi-criteria-search)

- [pyspark data processing in python on top of apache spark](https://ep2015.europython.eu/conference/talks/pyspark-data-processing-in-python-on-top-of-apache-spark)

- [Beyond the basics with Elasticsearch](https://ep2015.europython.eu/conference/talks/beyond-the-basics-with-elasticsearch)

- [Big Data with Python & Hadoop](https://ep2015.europython.eu/conference/talks/big-data-with-python-hadoop)

- [Bringing PostgreSQL towards zero downtime migration with Python](https://ep2015.europython.eu/conference/talks/bringing-postgresql-towards-zero-downtime-migration-with-python)

- [Speeding up search with locality sensitive hashing](https://ep2015.europython.eu/conference/talks/speeding-up-search-with-locality-sensitive-hashing)  
Неплохой доклад про data mining:
    * поиск соседей или похожих товаров
    * поиск похожих изображений
    * рекомендации
Используют hash table, balancing tree, random vector spliting, binary forest

- [efficient memorydisk data containers with python](https://ep2015.europython.eu/conference/talks/efficient-memorydisk-data-containers-with-python)

- https://github.com/Blosc/bcolz  
http://blosc.org/  
bcolz: columnar and compressed data containers (эфективен на современных cpu)

## scraping


- [frontera open source large scale web crawling framework](https://ep2015.europython.eu/conference/talks/frontera-open-source-large-scale-web-crawling-framework)  
http://scrapinghub.com/  
Расширенный паук для извлечения информации из веба + онлайн saas платформа.

- [advanced web scraping](https://ep2015.europython.eu/conference/talks/advanced-web-scraping)  
Хороший доклад об извлечении данных из веба с помощью scrapy, portia, frontera

- [dive into scrapy](https://ep2015.europython.eu/conference/talks/testing)

## testing


- [sustainable way of testing your code](https://ep2015.europython.eu/conference/talks/sustainable-way-of-testing-your-code)

- [lessons learned about testing and tdd](https://ep2015.europython.eu/conference/talks/lessons-learned-about-testing-and-tdd)

- [tdd is not about tests](https://ep2015.europython.eu/conference/talks/tdd-is-not-about-tests)

- [mashing up pytest coverage.py and ast.py to take tdd to a new level](https://ep2015.europython.eu/conference/talks/mashing-up-pytest-coveragepy-and-astpy-to-take-tdd-to-a-new-level)

- [tdd for apis](https://ep2015.europython.eu/conference/talks/tdd-for-apis)

- [12 years of pylint or how i stopped worrying and love the bugs](https://ep2015.europython.eu/conference/talks/12-years-of-pylint-or-how-i-stopped-worrying-and-love-the-bugs)  
Разработчик pylint о, собвственно, pylint

- [tdd the why the how and the when not](https://ep2015.europython.eu/conference/talks/tdd-the-why-the-how-and-the-when-not)

- [testing with two failure seeking missiles fuzzing and property based testing](https://ep2015.europython.eu/conference/talks/testing-with-two-failure-seeking-missiles-fuzzing-and-property-based-testing)  
Об тестировании рандомными данными в python

- [whats the fuzz all about randomized data generation for robust unit testing](https://ep2015.europython.eu/conference/talks/whats-the-fuzz-all-about-randomized-data-generation-for-robust-unit-testing)

- [faking it the art of testing using verified fakes](https://ep2015.europython.eu/conference/talks/faking-it-the-art-of-testing-using-verified-fakes)

- [Testing web apps with Selenium](https://ep2015.europython.eu/conference/talks/testing-web-apps-with-selenium)

- https://github.com/pacud/ep2015_pyteselenium  
pytest + selenium

- https://github.com/judy2k/ish  
Ish is a stupid library that allows you to test if a variable is true-ish or false-ish.

## CI & CD & deploy


- [the butler and the snake continuous integration for python](https://ep2015.europython.eu/conference/talks/the-butler-and-the-snake-continuous-integration-for-python)

- [a pythonic approach to continuous delivery](https://ep2015.europython.eu/conference/talks/a-pythonic-approach-to-continuous-delivery)

- [extending and embedding ansible with python](https://ep2015.europython.eu/conference/talks/extending-and-embedding-ansible-with-python)  
https://taiga.io/  Free. Open Source. Powerful. Taiga is a project management platform for startups and agile developers & designers who want a simple, beautiful tool that makes work truly enjoyable.  
Сама презентация о:
    * как вызвать ansible код из своего скрипта
    * как писать новое расширение для ansible

- [easy fullstack deployments](https://ep2015.europython.eu/conference/talks/easy-fullstack-deployments)  
We will cover from, the project creation (using Pyramid web framework), to maintaining a consistent deployment infrastructure using buildout and docker containers.

- [Continuous Deployment for webapps based on Django](https://ep2015.europython.eu/conference/talks/continuous-deployment-for-webapps-based-on-django)

## web & api


- [building mobile apis with services at yelp](https://ep2015.europython.eu/conference/talks/building-mobile-apis-with-services-at-yelp)

- [max realtime messaging and activity stream engine](https://ep2015.europython.eu/conference/talks/max-realtime-messaging-and-activity-stream-engine)  
https://github.com/UPCnet/max  
Multi-source user and application generated activity registry engine with asyncronous messaging and conversations facility.
http://max.beta.upcnet.es/docs/v3/en  
Самописный фреймворк поверх pyramid & gevent с собственным протоколом (json based) сообщений поверх mq.

- [reahl the python only web framework](https://ep2015.europython.eu/conference/talks/reahl-the-python-only-web-framework)  
Reahl is a full-featured web framework with a twist: with Reahl you write a web application purely in Python. HTML, JavaScript, CSS and all those cumbersome web technologies (and a few other lower level concerns) are hidden away from you

- [Solving the web most popular code shortening competition in Python](https://ep2015.europython.eu/conference/talks/solving-the-web-most-popular-code-shortening-competition-in-python)

- [Learnt lessons in a big Django Project](https://ep2015.europython.eu/conference/talks/learnt-lessons-in-a-big-django-project)

## parallel and asynchronous programming


- [mastering asyncio applications](https://ep2015.europython.eu/conference/talks/mastering-asyncio-applications)

- [understanding non blocking io](https://ep2015.europython.eu/conference/talks/understanding-non-blocking-io)

- [better asynchronous code with tornado and python3](https://ep2015.europython.eu/conference/talks/better-asynchronous-code-with-tornado-and-python-3)

- [distributed workflows with flowy](https://ep2015.europython.eu/conference/talks/distributed-workflows-with-flowy)  
https://flowy.readthedocs.org/en/latest/  
Однопоточное асинхронное приложение для запуска графа задач вроде celery.

- [Parallelism Shootout: threads vs asyncio vs multiple processes](https://ep2015.europython.eu/conference/talks/parallelism-shootout-threads-vs-asyncio-vs-multiple-processes)

## security


- [python security cryptography](https://ep2015.europython.eu/conference/talks/python-security-cryptography)  
https://speakerdeck.com/jmortega - остальные презентации спикера
    * pycrypto
    * cryptography
    * django-secure
    * securedjango.com
    * ponycheckup.com
    * owasp
    * stepic
    * stegano
    * cryptopng

- [taking the pain out of passwords and authentication](https://ep2015.europython.eu/conference/talks/taking-the-pain-out-of-passwords-and-authentication)  
- Introduce the new standards Universal Authentication Framework (UAF) & Universal Second Factor (U2F)
- Show how to integrate UAF/U2F in Django and other Python frameworks
- <del>Introduce Sonipass - a project to replace passwords, even on existing websites</del>

## documentation


- [MkDocs: Documenting projects with Markdow](https://ep2015.europython.eu/conference/talks/mkdocs-documenting-projects-with-markdown)  
Документация из markdown. WG Deployment использует в связке с readthedocs (docs.wargaming.net)
В последней версии много нового, нужно обновиться.

- [FOSS DOCS 101 (keep it simple, present!)](https://ep2015.europython.eu/conference/talks/foss-docs-101-keep-it-simple-present)  
Mikey Ariel - технический писатель в redhut про документацию.

    Правильные вопросы:
        - who are my readers?
        - what they want to know?
        - when they need this content?
        - where they consume this content?
        - why they even need this content?

    Поиск по документам важен.

    Devops for docs:
        - unified toolchain
        - use the same toolchain that used for code
        - continuous integration
        - iterative autoring
        - content curation
        - automation

    Docs or it didn't happen:
        - contribution guidelines
        - templates
        - collaboration and training

    "open help" project

## interesting frameworks and libraries


- [keynote towards a more effective decentralized web](https://ep2015.europython.eu/conference/talks/keynote-towards-a-more-effective-decentralized-web)  
http://ipfs.io/

- [python in the sky](https://ep2015.europython.eu/conference/talks/python-in-the-sky-in-flight-entertainment-with-python)  
single-threaded  
http://immfly.com/ - Wi-Fi с рекламой и шопингом в самалетах.
Синхронизация в ангаре с использовпнием ansible pull.

- [introduction to baserock](https://ep2015.europython.eu/conference/talks/introduction-to-baserock)  
http://wiki.baserock.org/  
Система сборки, работает на unix, умеет:
    * metadata
    * overrides
    * cache
    * сборка с нуля в chroot
    * образы для docker, openstack, блочный img
    * browser board
    * etc...

- [odoo the underdog python killer app a python framework for web based business apps](https://ep2015.europython.eu/conference/talks/odoo-the-underdog-python-killer-app-a-python-framework-for-web-based-business-apps)  
Платформа и фрэймворк для создания бизнес приложений.
Конструктор, файлы конфигураций в формате xml, очень большой и кастомизируемый.

- [python gamedev mlg](https://ep2015.europython.eu/conference/talks/python-gamedev-mlg)  
https://www.youtube.com/watch?v=PIcCsZ3Nk8I  
Presentation of Kobra, a modern open source Python game development framework with ECS (Entity Component System) architecture and C++ bindings.
Beta обещают в декабре.

- [numpy vectorize your brain](https://ep2015.europython.eu/conference/talks/numpy-vectorize-your-brain)  
Базовое описание numpy

- [gitfs building a filesystem in python](https://ep2015.europython.eu/conference/talks/gitfs-building-a-filesystem-in-python)  
Монтирование репозитория git как набор каталогов:
    * rw директория с head
    * ro структура каталогов по комитам
    * кэширование на 3 уровнях
    * лимиты на бинарные файлы
Использует pygit2 + fusepy

- ["It's about time to take your medication!" or how to write a friendly reminder bot ;-)](https://ep2015.europython.eu/conference/talks/its-about-time-to-take-your-medication-or-how-to-write-a-friendly-reminder-bot) 

- https://pythonhosted.org/pulsar  
Event driven concurrent framework for python. With pulsar you can write asynchronous servers performing one or several activities in different threads and/or processes

- https://github.com/cenkalti/exceptional-python  
a python client for Exceptional, a service which tracks errors in your web apps

- https://github.com/pyland/pyland  
A game to help children learn Python

- https://github.com/ionelmc/python-manhole  
Debugging manhole for python applications

- https://github.com/Friz-zy/pyspaces  
Works with Linux namespaces througth glibc with pure python 

- https://borgbackup.github.io/borgbackup/  
Borg is a deduplicating backup program. Optionally, it also supports compression and authenticated encryption.

- https://github.com/conda/conda  
Cross-platform, Python-agnostic binary package manager http://conda.pydata.org

- http://www.qtile.org/  
A full-featured, hackable tiling window manager written and configured in Python
