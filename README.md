<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
	<head>
		<title>myApp - Development Environment</title>

		<!-- General META -->
		<meta charset="utf-8">
		<meta http-equiv="Content-type" content="text/html;charset=UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
		<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1">
		<meta name="apple-mobile-web-app-capable" content="yes">
		<meta name="apple-mobile-web-app-status-bar-style" content="black">

		<!-- Semantic META -->
		<meta name="keywords" content="">
		<meta name="description" content="">

		<!-- Facebook META -->
		<meta property="fb:app_id" content="APP_ID">
		<meta property="og:site_name" content="myApp - Development Environment">
		<meta property="og:title" content="myApp - Development Environment">
		<meta property="og:description" content="">
		<meta property="og:url" content="http://localhost:3000/">
		<meta property="og:image" content="/img/brand/logo.png">
		<meta property="og:type" content="website">

		<!-- Twitter META -->
		<meta name="twitter:title" content="myApp - Development Environment">
		<meta name="twitter:description" content="">
		<meta name="twitter:url" content="http://localhost:3000/">
		<meta name="twitter:image" content="/img/brand/logo.png">

		<!-- Fav Icon -->
		<link href="/modules/core/img/brand/favicon.ico" rel="shortcut icon" type="image/x-icon">

		<!--Application CSS Files-->
		<link rel="stylesheet" href="lib/bootstrap/dist/css/bootstrap.css">
		<link rel="stylesheet" href="lib/bootstrap/dist/css/bootstrap-theme.css">
		<link rel="stylesheet" href="modules/core/css/core.css">
		<link rel="stylesheet" href="modules/users/css/users.css">

		<!-- HTML5 Shim -->
		<!--[if lt IE 9]>
			<script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
		<![endif]-->
	</head>

	<body class="ng-cloak">
		<header data-ng-include="'/modules/core/views/header.client.view.html'" class="navbar navbar-fixed-top navbar-default"></header>
		<section class="content">
			<section class="container">
				<section data-ui-view></section>
			</section>
		</section>

		<!--Embedding The User Object-->
		<script type="text/javascript">
			var user = "";
		</script>

		<!--Application JavaScript Files-->
		<script type="text/javascript" src="lib/angular/angular.js"></script>
		<script type="text/javascript" src="lib/angular-resource/angular-resource.js"></script>
		<script type="text/javascript" src="lib/angular-cookies/angular-cookies.js"></script>
		<script type="text/javascript" src="lib/angular-animate/angular-animate.js"></script>
		<script type="text/javascript" src="lib/angular-touch/angular-touch.js"></script>
		<script type="text/javascript" src="lib/angular-sanitize/angular-sanitize.js"></script>
		<script type="text/javascript" src="lib/angular-ui-router/release/angular-ui-router.js"></script>
		<script type="text/javascript" src="lib/angular-ui-utils/ui-utils.js"></script>
		<script type="text/javascript" src="lib/angular-bootstrap/ui-bootstrap-tpls.js"></script>
		<script type="text/javascript" src="config.js"></script>
		<script type="text/javascript" src="application.js"></script>
		<script type="text/javascript" src="modules/core/core.client.module.js"></script>
		<script type="text/javascript" src="modules/users/users.client.module.js"></script>
		<script type="text/javascript" src="modules/core/config/core.client.routes.js"></script>
		<script type="text/javascript" src="modules/core/controllers/header.client.controller.js"></script>
		<script type="text/javascript" src="modules/core/controllers/home.client.controller.js"></script>
		<script type="text/javascript" src="modules/core/services/menus.client.service.js"></script>
		<script type="text/javascript" src="modules/users/config/users.client.config.js"></script>
		<script type="text/javascript" src="modules/users/config/users.client.routes.js"></script>
		<script type="text/javascript" src="modules/users/controllers/authentication.client.controller.js"></script>
		<script type="text/javascript" src="modules/users/controllers/password.client.controller.js"></script>
		<script type="text/javascript" src="modules/users/controllers/settings.client.controller.js"></script>
		<script type="text/javascript" src="modules/users/services/authentication.client.service.js"></script>
		<script type="text/javascript" src="modules/users/services/users.client.service.js"></script>

		<!--Livereload script rendered -->
		<script type="text/javascript" src="http://localhost:35729/livereload.js"></script>
	</body>
</html>
