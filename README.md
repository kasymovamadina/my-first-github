<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Food, LLC</title>
  <!-- Bootstrap 3.3 CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <!-- Custom CSS -->
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <!-- Brand -->
      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-menu">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#">Food, LLC</a>
      </div>

      <!-- Mobile dropdown menu (visible only on xs) -->
      <div class="collapse navbar-collapse visible-xs" id="navbar-menu">
        <ul class="nav navbar-nav">
          <li><a href="#">Chicken</a></li>
          <li><a href="#">Beef</a></li>
          <li><a href="#">Sushi</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Main content -->
  <div class="container">
    <!-- Centered heading -->
    <div class="row">
      <div class="col-xs-12 text-center">
        <h1>Our Menu</h1>
      </div>
    </div>

    <!-- Tall section -->
    <div class="row">
      <div class="col-xs-12">
        <div class="tall-section">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p>Additional content to make the section tall enough for scrolling...</p>
        </div>
      </div>
    </div>
  </div>

  <!-- jQuery + Bootstrap JS -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</body>
</html>
