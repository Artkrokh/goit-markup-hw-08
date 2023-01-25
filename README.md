# goit-markup-hw-03
<!DOCTYPE html>
<html lang="uk">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>WebStudio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.0.0/modern-normalize.css"
    />
    <link rel="stylesheet" href="./css/styles.css" />
  </head>
  <body class="body">
    <header class="header">
      <div class="container header-container">
        <nav class="nav">
          <a href="./index.html" class="logo-title"
            >Web<span class="logo-head">Studio</span></a
          >
          <!-- Links to other pages or sections of the current page -->
          <ul class="nav-list">
            <li class="nav-link">
              <a class="nav-text current" href="./index.html">Студія</a>
            </li>
            <li class="nav-link">
              <a class="nav-text" href="./portfolio.html">Портфоліо</a>
            </li>
            <li class="nav-link"><a class="nav-text" href="">Контакти</a></li>
          </ul>
        </nav>
        <ul class="contacts">
          <li class="contacts-link">
            <a class="contacts-text" href="mailto:info@devstudio.com">
              <svg class="contacts-icon" width="16" height="12">
                <use href="./images/icons.svg#icon-envelope"></use>
                </svg>info@devstudio.com</a>
          </li>
          <li class="contacts-link">
            <a class="contacts-text" href="tel:+380961111111">
              <svg class="contacts-icon" width="10" height="16">
                <use href="./images/icons.svg#icon-smartphone"></use>
                </svg>+38 096 111 11 11</a>
          </li>
        </ul>
      </div>
      <!-- A link to an external resource will open in the current tab -->
    </header>