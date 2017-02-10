# Progresser
Indicate to your users with style. Designed by [planlodge](https://github.com/planlodge).

![Image](https://github.com/planlodge/Progresser/blob/master/demo/img/screen1.gif?raw=true)

[![Build Status](https://travis-ci.org/stevenbenner/jquery-powertip.svg?branch=master)](https://travis-ci.org/stevenbenner/jquery-powertip)
![Release Version](http://img.shields.io/github/release/stevenbenner/jquery-powertip.svg)
![License](https://img.shields.io/packagist/l/doctrine/orm.svg)


## Getting Started

 1. Include jQuery in your code.

		<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
 
 2. Download and include the progresser.js and progresser.css files.
 
 		<link rel="stylesheet" href="../build/progresser.css" />
		<script src="../build/progresser.js"></script>
 3. Pick your selector and apply progresser to it!
 	
		<progress class="progresser" value="0"></progress>
		$('.progresser').progresser();
 		

## Full Example

[**Demo Link**](https://planlodge.github.io/Progresser/demo/) 

    <!DOCTYPE html>
	<html lang="en-US">

	<head>
	    <meta charset="utf-8">
	    <title>Progresser Demo - Planlodge</title>
	    <meta http-equiv="X-UA-Compatible" content="IE=edge">
	    <meta name="Language" content="en">
	    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no, minimal-ui">
	    <link rel="icon" type="image/png" href="img/favicon.png" />
	    <link rel="stylesheet" href="../build/progresser.css" />
	    <link rel="stylesheet" href="css/styles.css" />
	</head>

	<body>

	<progress class="progresser" max="0" value="0"></progress>

	<div id="content" class="demo">
	    <div id="myContent">
		<p>
		    Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus. Donec vitae sapien ut libero venenatis faucibus. Nullam quis ante. Etiam sit amet orci eget eros faucibus tincidunt. Duis leo. Sed fringilla mauris sit amet nibh. Donec sodales sagittis magna. Sed consequat, leo eget bibendum sodales, augue velit cursus nunc,
		</p>
	    </div>

	    <p>
		Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus. Donec vitae sapien ut libero venenatis faucibus. Nullam quis ante. Etiam sit amet orci eget eros faucibus tincidunt. Duis leo. Sed fringilla mauris sit amet nibh. Donec sodales sagittis magna. Sed consequat, leo eget bibendum sodales, augue velit cursus nunc,
	    </p>
	</div>



	<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
	<script src="../build/progresser.js"></script>
	<script>
	    $('.progresser').progresser({
		selectedContent: 'myContent',
		onBottomAction: function() {
		    alert("Bottom");
		},
		onTopAction: function() {
		    alert("Top");
		}
	    });
	</script>
	</body>

	</html>
	
## Options

- **selectedContent** - Id of the content you'd like to keep track of.

- **onBottomAction()** - On hitting the bottom of the page, add any code here.

- **onTopAction()** - Upon returning to the top of the page, add any code here.

## Updates in V2

Browser Resize Support


## License

Progresser is licensed under the [MIT license](http://opensource.org/licenses/MIT).

