# elementor-crash

the youtube vid:
https://www.youtube.com/watch?v=GXFvHMG-Qvk&ab_channel=JohnMogi


i made a huge 60 rev above 25 templates post...

https://elementor.com/help/safe-mode-not-solving-problem/?utm_source=safe-mode&utm_medium=wp-dash&utm_campaign=learn

wp-config


define( 'WP_DEBUG', true );


define( 'WP_MEMORY_LIMIT', '512M' );

	
define( 'WP_POST_REVISIONS', 20 );

1. maintnance:
solve issue where elementor crashes after save
(import big homepage, cause mem leak)

make an import of 50 imports and revisions

target: create a huge json file from elementor - > site.json


0. use all in one to transfer between local and site


1.0 limit post revisions
1.5 clean old  post revisions

1.0 backup - backup buddy, aio, manual

2.0 clear transients with wp-optimize
2. cli - clear transients

