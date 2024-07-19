# Top WordPess Functions

Here is the top 100 WordPress functions: it is the list of the most often used WordPress functions. If you are a WordPress Developer, you must know the Top 100 WordPress functions deeply.

## The 100 WordPress Functions That You Have to Know (2024)

Here is the top 100 WordPress functions: it is the list of the most often used WordPress native functions.

| Rank | Function                     | Description                                                                                          |
|------|------------------------------|------------------------------------------------------------------------------------------------------|
| 1    | get_permalink                | Retrieves the full permalink for the current post or post ID.                                        |
| 2    | the_permalink                | Retrieves and displays the full permalink for the current post or post ID.                           |
| 3    | has_excerpt                  | Determines whether the post has an excerpt.                                                          |
| 4    | get_the_excerpt              | Retrieves the excerpt for the current post. By default, excerpt length is set to 55 words.           |
| 5    | the_excerpt                  | Retrieves and displays the excerpt for the current post.                                             |
| 6    | get_the_post_thumbnail       | Retrieves the post thumbnail.                                                                        |
| 7    | has_post_thumbnail           | Determines whether the current post has a featured image attached.                                   |
| 8    | get_cat_ID                   | Retrieves the ID of a category from its name.                                                        |
| 9    | get_cat_name                 | Retrieves the name of a category from its ID.                                                        |
| 10   | get_categories               | Retrieves category objects.                                                                          |
| 11   | get_category_link            | Retrieves category link URL.                                                                         |
| 12   | single_cat_title             | Retrieves and displays page title for a category archive.                                            |
| 13   | wp_list_categories           | Retrieves and displays the HTML list of categories.                                                  |
| 14   | register_post_type           | Registers a custom post type.                                                                        |
| 15   | register_taxonomy            | Registers a custom taxonomy.                                                                         |
| 16   | get_post_meta                | Retrieves a post meta field for the given post ID.                                                   |
| 17   | add_meta_box                 | Adds a meta box to one or more screens.                                                              |
| 18   | the_post                     | Checks whether the loop has started and sets the next post to be displayed each time in the loop.    |
| 19   | get_the_ID                   | Retrieves the ID of the current post in the WordPress loop.                                          |
| 20   | the_ID                       | Retrieves and displays the ID of the current post in the WordPress loop.                             |
| 21   | get_the_author               | Retrieves the display name of the author in the WordPress loop.                                      |
| 22   | the_author                   | Retrieves and displays the name of the author for the current post.                                  |
| 23   | get_the_content              | Fetches the content of the current post.                                                             |
| 24   | the_content                  | Fetches and displays the content of the current post in the WordPress loop.                          |
| 25   | get_the_title                | Retrieves the title of the current post in the loop.                                                 |
| 26   | the_title                    | Retrieves and displays the title of the current post in the loop.                                    |
| 27   | current_user_can             | Determines whether the current user has the specified capability.                                    |
| 28   | is_super_admin               | Determines whether the user has the highest level of administrative privileges on a WordPress site.  |
| 29   | is_user_logged_in            | Checks whether the current user is logged in.                                                        |
| 30   | wp_login_form                | Outputs a login form anywhere on the WordPress site with the default options.                        |
| 31   | comment_form                 | Displays an HTML comment form within a WordPress template file.                                      |
| 32   | comments_number              | Displays the number of comments for the current post.                                                |
| 33   | get_avatar                   | Retrieves a user's avatar (Gravatar profile picture) based on their provided email address.          |
| 34   | wp_list_comments             | Retrieves and displays a list of comments for the current post. Used within the comments.php template file. |
| 35   | comment_author               | Fetches and displays the name of the author for the current comment.                                 |
| 36   | comment_date                 | Retrieves and displays the date of the current comment.                                              |
| 37   | comment_time                 | Displays the time of the current comment in a WordPress post.                                        |
| 38   | get_comment_date             | Retrieves the date of the current comment in a WordPress post or page.                               |
| 39   | get_comment_time             | Retrieves the time of the current comment in a WordPress post or page.                               |
| 40   | get_header                   | Includes a header template for a theme. If a name is passed into the function, the specified header will be included. |
| 41   | get_footer                   | Includes a footer template for a WordPress theme. If a name is passed as an argument, the specialized footer will be included. |
| 42   | comments_template            | Includes a comment template in post. If a file argument is passed, the specified comments file will be loaded. It will not display the comments template if not on a single post or page, or if the post does not have comments. |
| 43   | get_sidebar                  | Includes a sidebar template for a WordPress theme. If a name is passed as an argument, the specified sidebar will be included. |
| 44   | get_search_form              | Displays a search form in a WordPress theme. Attempts to load the searchform.php file; if not found, displays the default search form. |
| 45   | add_image_size               | Registers a new image size in WordPress.                                                             |
| 46   | add_theme_support            | Enables support for certain theme features.                                                          |
| 47   | body_class                   | Assigns additional CSS classes for the body element based on the WordPress template files.           |
| 48   | current_theme_supports       | Checks whether the theme supports a certain feature.                                                 |
| 49   | register_sidebars            | Registers one or more sidebars in WordPress.                                                         |
| 50   | dynamic_sidebar              | Displays a dynamic sidebar on the WordPress website.                                                 |
| 51   | get_stylesheet_directory_uri | Retrieves the stylesheet directory URI for the current theme.                                        |
| 52   | register_nav_menus           | Registers one or more navigation menu locations in WordPress.                                        |
| 53   | has_nav_menu                 | Determines whether a registered nav menu location has a menu assigned to it.                         |
| 54   | wp_nav_menu                  | Displays a navigation menu in WordPress. A `theme_location` parameter is used to display the menu assigned to that location. |
| 55   | wp_title                     | Displays the dynamic page title in the browser tab, if the theme supports the title tag.             |
| 56   | esc_html                     | Escapes mixed text by converting special characters to equivalent HTML entities for safe use.        |
| 57   | esc_url                      | Checks and sanitizes a URL. Removes specific characters from the URL and replaces ampersands if displaying. |
| 58   | _e                           | Displays a translated text in WordPress.                                                             |
| 59   | the_date                     | Displays or retrieves the date on which the current post was created.                                |
| 60   | get_the_date                 | Retrieves the date the current post was created.                                                     |
| 61   | the_time                     | Displays or retrieves the time at which the current post was created.                                |
| 62   | get_the_time                 | Retrieves the time the current post was created.                                                     |
| 63   | the_modified_time            | Displays the time at which the post was last modified.                                               |
| 64   | get_the_modified_time        | Retrieves the time at which the post was last modified.                                              |
| 65   | the_modified_date            | Displays the date on which the post was last modified.                                               |
| 66   | get_the_modified_date        | Retrieves the date on which the post was last modified.                                              |
| 67   | get_site_url                 | Retrieves the URL for a given site where the WordPress application is installed.                     |
| 68   | site_url                     | Retrieves and displays the URL for a given site where the WordPress application is installed.        |
| 69   | is_category                  | Determines whether the current page is an existing archive page.                                     |
| 70   | is_front_page                | Determines whether the current page is the front page on a WordPress website. Returns true for a static front page or page of recent posts. |
| 71   | is_page                      | Determines whether the query is for an existing single page.                                          |
| 72   | is_home                      | Checks whether the current page is the homepage on a WordPress website, displaying latest blog post content. |
| 73   | is_404                       | Determines whether the query has resulted in a 404 HTTP page not found error.                         |
| 74   | is_search                    | Determines whether the search results page is displayed.                                              |
| 75   | is_single                    | Determines whether the query is for an existing single post.                                          |
| 76   | get_bloginfo                 | Retrieves information about the current site.                                                         |
| 77   | query_posts                  | Sets up the post loop with query parameters.                                                          |
| 78   | get_posts                    | Retrieves an array of the latest posts, or posts based on a set of parameters.                        |
| 79   | wp_enqueue_script            | Registers and enqueues a script.                                                                      |
| 80   | wp_enqueue_style             | Enqueues a CSS stylesheet in WordPress.                                                               |
| 81   | wp_head                      | Prints scripts or data before the closing head tag by firing the `wp_head` action hook.               |
| 82   | wp_footer                    | Prints scripts or data before the closing body tag by firing the `wp_footer` action hook.             |
| 83   | get_template_part            | Includes the named template part into a template. Can include the same partial template file multiple times. |
| 84   | apply_filters                | Calls a callback function attached to a filter hook. Filters always return a filtered value after all hooked functions are applied. |
| 85   | add_action                   | Attaches a callback function to an action hook. WordPress calls action hooks at specific points or when events occur. |
| 86   | register_setting             | Registers a setting and its data.                                                                     |
| 87   | add_shortcode                | Registers a new shortcode in WordPress.                                                               |
| 88   | do_shortcode                 | Retrieves the content of the shortcode and filters it through their hooks.                            |
| 89   | plugin_dir_path              | Retrieves the directory's full path where the current file is located.                                |
| 90   | register_activation_hook     | Sets or registers the activation hook for a plugin. Called when the plugin is activated.              |
| 91   | register_deactivation_hook   | Sets or registers the deactivation hook for a plugin. Called when the plugin is deactivated.          |
| 92   | is_plugin_active             | Determines whether a plugin is active.                                                                |
| 93   | is_plugin_inactive           | Checks whether a plugin is inactive.                                                                  |
| 94   | register_widget              | Registers a widget in WordPress.                                                                      |
| 95   | is_serialized                | Determines whether the provided string is created using the PHP serialized function.                  |
| 96   | add_option                   | Adds a new option if it does not exist.                                                               |
| 97   | get_option                   | Retrieves an option value based on an option name.                                                    |
| 98   | add_menu_page                | Adds a top-level menu page.                                                                           |
| 99   | add_options_page             | Registers a new option page under the settings menu.                                                  |
| 100  | wp_mail                      | Sends an email in WordPress.                                                                          |

Source: https://www.linkedin.com/pulse/100-most-used-wordpress-functions-list-examples-arunlal-panja/
