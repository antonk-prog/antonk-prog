<br clear="both">

<div align="center">
<img alt="Coder GIF" height=250 width=350 src="https://jimmyhoe.com/images/giphy-2.gif" />
</div>


###

<div align="center">
  <a href="https://t.me/antonk_prog" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Telegram&logo=telegram&label=&color=2CA5E0&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="telegram logo"  />
  </a>
</div>

###

<h3 align="left">👩‍💻  Обо мне</h3>

<p>Меня вдохновляет системное программирование и разработка высокоэффективного ПО на <strong>C/C++</strong>. Именно в этой области я хочу развиваться профессионально и строить карьеру.</p> 
<ul> 
  <li><strong>1 год коммерческого опыта</strong> в компании <strong><a href="https://eidos-robotics.ru/"> Eidos Robotics</a></strong> на позиции младшего инженер-программиста С++/Python</li>
  <li>Заканчиваю обучение в <string>школе 21</string> по разработческой специальности на C/C++</li>
  <li>Хорошо владею <strong>C/C++</strong>, включая <code>STL</code>, современные стандарты <code>C++11/14/17</code>, основы многопоточности, RAII и умные указатели</li>
  <li>Есть практический опыт в написании <strong>сетевых приложений</strong> на C/C++ (сокеты, TCP/UDP)</li>
  <li>Свободно ориентируюсь в <strong>Linux</strong>, использую его как основную операционную систему для работы и разработки</li>
  <li>Опытный пользователь <strong>Git</strong>: умею вести историю, работать с ветками, решать конфликты, писать понятные коммиты и организовывать командную работу</li>
  <li>Работаю с <strong>CMake</strong>, умею структурировать проекты и подключать библиотеки, в том числе через вложенные CMakeLists</li>
  <li>Имею опыт внедрения <strong>баз данных</strong> в приложения на C/C++ (в том числе через PostgreSQL)</li> 
</ul> 
<p>Я открытый и гибкий в обучении, всегда готов осваивать новые инструменты, улучшать код и развивать техническое мышление. Люблю, когда код — это не только решение задачи, но и пример читаемости, устойчивости.</p>

###

<h3 align="left">🧩 Проекты</h3>
<ul>
  <li>
    <strong>Десктопное приложение для управления персоналом (Qt/C++)</strong>
    <ul>
      <li>
        <details>
          <summary>Демонстрация работы приложения</summary> 
          <div>
            <div align="center">
              <img alt="Демонстрация приложения" height="479" width="800" src="qt_example.gif">
            </div>
          </div>
        </details>
      </li>
      <li>Основной функционал:
        <ul>
          <li>Добавление/редактирование/удаление сотрудников</li>
          <li>Поиск по ФИО, должности, стажу</li>
          <li>Увольнение с указанием причины</li>
        </ul>
      </li>
      <li>Технические особенности:
        <ul>
          <li>Сериализация данных через QDataStream</li>
          <li>Поддержка загрузки изображений</li>
          <li>Два режима отображения (список/таблица)</li>
        </ul>
      </li>
      <li>Стек технологий:
        <ul>
          <li>C++ (ООП, STL)</li>
          <li>Qt (QWidgets, сигналы/слоты)</li>
          <li>Кастомизированные виджеты</li>
        </ul>
      </li>
      <li>
        <a href="https://github.com/antonk-prog/employee-manager-qt">Ссылка на проект</a>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li>
    <strong>Роботизированный захват предметов с компьютерным зрением</strong>
    <ul>
      <li>
        <details>
          <summary>Демонстрация работы</summary>
          <div>
            <div align="center">
              <img alt="Демонстрация работы" height="479" width="800" src="robotics_little.gif">
            </div>
          </div>
        </details>
      </li>
       <li>Основной функционал:
        <ul>
          <li>Распознавание и локализация объектов с использованием компьютерного зрения (OpenCV, YOLO)</li>
          <li>Интеграция с робототехническим API для управления манипулятором (Python, C++)</li>
          <li>Анализ 2D-изображений и расчёт оптимальных траекторий захвата</li>
        </ul>
      </li>
      <li>Технические особенности:
        <ul>
          <li>Алгоритмы точного позиционирования и управления захватом</li>
          <li>Инструменты калибровки камеры и привязки координатных систем</li>
          <li>Модуль тестирования точности системы и проверки стабильности работы</li>
        </ul>
      </li>
      <li>Стек технологий:
        <ul>
          <li>Python</li>
          <li>C++</li>
          <li>OpenCV</li>
          <li>Yolo</li>
          <li>Робототехническое API</li>
          <li>Scipy</li>
          <li>Numpy</li>
        </ul>
      </li>
      <li>
        <details>
          <summary>Подробное описание</summary>
          <div>
            <p> Программный комплекс предназначен для автоматизированного захвата предметов из контейнера с помощью камеры и набора интеллектуальных алгоритмов. Его основная задача — дать роботу «зрение» и способность действовать самостоятельно в условиях, где предметы лежат неупорядоченно. </p> <p> Главный модуль системы объединяет сразу несколько компонентов: он получает изображение с камеры, с помощью технологий компьютерного зрения (OpenCV) и нейросетевого распознавания (Yolo) определяет положение нужных объектов, затем рассчитывает оптимальные траектории и передаёт команды на управление роботом через соответствующее API. Этот модуль фактически связывает «глаза» и «руки» машины, позволяя ей точно и надёжно выполнять задачи захвата. </p> <p> Дополнительно в составе комплекса реализованы вспомогательные инструменты: утилита калибровки камеры, которая позволяет добиться высокой точности распознавания и соответствия координат, а также модуль проверки точности, с помощью которого можно убедиться, что система работает корректно и стабильно. Всё это делает комплекс универсальным решением для автоматизации на производстве или в робототехнических проектах. </p>
          </div>
        </details>
      </li>
    </ul>
  </li>
</ul>


###

<h3 align="left">🛠 Стек технологий:</h3>

###

<div align="left">

  <img src="https://cdn.worldvectorlogo.com/logos/c.svg" height="40" alt="c++ logo"  />
  <img width="12" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/C_Programming_Language.svg" height="40" alt="c logo"  />
  <img width="12" />
  <img src="https://cdn.worldvectorlogo.com/logos/linux.svg" height="40" alt="linux"  />
  <img width="12" />  
  <img src="https://www.svgrepo.com/show/354243/qt.svg" height="40" alt="qt logo"  />
  <img width="12" />
  <img src="https://www.vectorlogo.zone/logos/cmake/cmake-ar21.svg" height="40" alt="cmake"  />
  <img width="12" />
  <img src="https://www.svgrepo.com/show/452091/python.svg" height="40" alt="python"  />
  <img width="12" />
  <img src="https://www.svgrepo.com/show/331760/sql-database-generic.svg" height="40" alt="sql"  />
  <img width="12" />
  <img src="https://cdn.worldvectorlogo.com/logos/git.svg" height="40" alt="git"  />
  <img width="12" />
  <img src="https://cdn.worldvectorlogo.com/logos/docker.svg" height="40" alt="docker"  />
  <img width="12" />
</div>
