<br clear="both">

<div align="center">
<img alt="Coder GIF" height=250 width=350 src="https://jimmyhoe.com/images/giphy-2.gif" />
</div>

###

<h1 align="center">Привет👋 Меня зовут Антон!</h1>

###

<div align="center">
  <a href="https://t.me/antonk_prog" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Telegram&logo=telegram&label=&color=2CA5E0&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="telegram logo"  />
  </a>
</div>

###

<h3 align="left">👩‍💻  Обо мне</h3>

###

- Разработал десктопное приложение для управления персоналом на Qt (C++), обеспечивающее удобный учет сотрудников с возможностью добавления, редактирования, удаления и поиска по ключевым параметрам (ФИО, должность).
<details>
  <summary>Посмотреть детали</summary>
  <div align="center">
  <p>десктоп-приложение на C++ с использованием Qt Framework для управления базой данных сотрудников. Включает функции добавления, редактирования, удаления и поиска записей с возможностью фильтрации по различным полям (ФИО, должность, стаж), а также увольнения с указанием причины. Реализована сериализация данных через QDataStream, поддержка загрузки изображений и два режима отображения (список/таблица). Стек технологий: C++ (ООП, STL), Qt (QWidgets, сигналы/слоты, QListWidget, QLineEdit, QDateEdit), кастомизированные виджеты. Проект демонстрирует навыки разработки GUI-приложений, работы с данными и событиями, а также применения паттернов проектирования в рамках Qt. Подходит для вакансий C++/Qt Developer.</p>
  <img alt="Coder GIF" height=479 width=800 src="qt_example.gif" />
  </div>
</details>

<div class="project-card">
  <div class="project-header">
    <h2>👨‍💼 Employee Management Desktop App (Qt/C++)</h2>
    <div class="tech-stack">
      <span class="tech-tag">C++</span>
      <span class="tech-tag">Qt Framework</span>
      <span class="tech-tag">QWidgets</span>
      <span class="tech-tag">OOP</span>
      <span class="tech-tag">STL</span>
    </div>
  </div>
  
  <div class="project-content">
    <div class="project-details">
      <h3>🔍 Описание проекта</h3>
      <p>Десктопное приложение для управления базой данных сотрудников с интуитивным интерфейсом и расширенными функциями работы с данными.</p>
      
      <div class="features">
        <h4>✨ Основные функции:</h4>
        <ul>
          <li>✅ CRUD операции с записями сотрудников</li>
          <li>🔍 Поиск и фильтрация по ФИО, должности, стажу</li>
          <li>📷 Загрузка и отображение фотографий</li>
          <li>📅 Увольнение с указанием причины</li>
          <li>🔄 Два режима отображения (список/таблица)</li>
          <li>💾 Сериализация данных через QDataStream</li>
        </ul>
      </div>
      
      <div class="implementation">
        <h4>🛠️ Реализация:</h4>
        <ul>
          <li>Кастомизированные виджеты и диалоговые окна</li>
          <li>Модель-представление для работы с данными</li>
          <li>Механизм сигналов/слотов для обработки событий</li>
          <li>Паттерны проектирования Qt</li>
        </ul>
      </div>
    </div>
    
    <details class="demo-section">
      <summary>🎥 Демонстрация работы</summary>
      <div class="demo-content">
        <img alt="Демонстрация приложения" src="qt_example.gif" class="demo-gif" />
        <p class="demo-description">Наглядно показаны основные функции приложения: добавление нового сотрудника, поиск по базе, переключение между режимами отображения и другие возможности интерфейса.</p>
      </div>
    </details>
  </div>
</div>

<style>
.project-card {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  max-width: 900px;
  margin: 20px auto;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  background: #fff;
  color: #333;
  line-height: 1.6;
}

.project-header {
  padding: 20px;
  background: linear-gradient(135deg, #2c3e50, #4ca1af);
  color: white;
}

.project-header h2 {
  margin: 0;
  font-size: 24px;
}

.tech-stack {
  margin-top: 10px;
}

.tech-tag {
  display: inline-block;
  background: rgba(255, 255, 255, 0.2);
  padding: 3px 8px;
  margin-right: 8px;
  border-radius: 4px;
  font-size: 12px;
}

.project-content {
  padding: 20px;
}

.project-details h3 {
  color: #2c3e50;
  border-bottom: 2px solid #eee;
  padding-bottom: 8px;
  margin-top: 0;
}

.features, .implementation {
  margin: 15px 0;
}

.features h4, .implementation h4 {
  color: #4ca1af;
  margin-bottom: 8px;
}

.features ul, .implementation ul {
  padding-left: 20px;
}

.features li {
  margin-bottom: 6px;
  list-style-type: none;
  position: relative;
  padding-left: 25px;
}

.features li:before {
  content: "";
  position: absolute;
  left: 0;
  top: 7px;
  width: 8px;
  height: 8px;
  background: #4ca1af;
  border-radius: 50%;
}

.demo-section {
  margin-top: 25px;
  border: 1px solid #eee;
  border-radius: 8px;
  padding: 12px;
}

.demo-section summary {
  font-weight: bold;
  cursor: pointer;
  outline: none;
  color: #2c3e50;
}

.demo-content {
  margin-top: 15px;
  text-align: center;
}

.demo-gif {
  max-width: 100%;
  border-radius: 6px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.demo-description {
  margin-top: 10px;
  font-size: 14px;
  color: #666;
}
</style>


Разработал программный комплекс для автоматизированного Bin Picking, включающий интеграцию системы компьютерного зрения (OpenCV, Yolo) с робототехническим API через Python. Реализовал алгоритмы обработки 2D-данных, планирования траекторий и управления захватом робота, а также вспомогательные утилиты для калибровки камер и тестирования их точности.


###

<h3 align="left">🛠 Технологии:</h3>

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
  <img src="https://www.svgrepo.com/show/331760/sql-database-generic.svg" height="40" alt="sql"  />
  <img width="12" />
  <img src="https://cdn.worldvectorlogo.com/logos/git.svg" height="40" alt="git"  />
  <img width="12" />
  <img src="https://cdn.worldvectorlogo.com/logos/docker.svg" height="40" alt="docker"  />
  <img width="12" />
  
</div>

<details>
  <summary>Click👆</summary>
  <pre>
  🤷‍♂️
  </pre>
</details>

###
