# Features
- The theme primarily includes a simple Header and a Footer.
- The Header consists of the Baizonn Learning Centre Logo and a navigation bar.
- The navigation bar includes links to five different pages:

  - [Home](https://cp3402-team-a.com/) 
  - [About Us](https://cp3402-team-a.com/about-us-2/)  
  - [Registration](https://cp3402-team-a.com/registration/)
  - [Schedule](https://cp3402-team-a.com/schedule/)
  - [Contact Us](https://cp3402-team-a.com/contact-us/)

- The Website Logo includes a link to the home page.
- The Footer includes the contact information for General Enquires.

# Files
- header.php
```php
<nav id="site-navigation" class="main-navigation">
			<button class="menu-toggle" aria-controls="primary-menu" aria-expanded="false"><?php esc_html_e( 'Primary Menu', 'baizonn' ); ?></button>
			<?php
			wp_nav_menu(
				array(
					'theme_location' => 'menu-1',
					'menu_id'        => 'primary-menu',
				)
			);
			?>
		</nav><!-- #site-navigation -->
```
