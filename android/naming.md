# Naming

### Layouts:

| Component           | Class Name       | Resource Name         |
| ------------------- | ---------------- | --------------------- |
| Activity            | SignUpActivity   | activity_sign_up.xml  |
| Fragment            | ProfileFragment  | fragment_profile.xml  |
| Dialog              | FilterDialog     | dialog_filter.xml     |
| Item (RecyclerView) | FeedItem         | item_feed.xml         |
| View                | RatingView       | view_rating.xml       |
| Toast               | ErrorToast       | toast_error.xml       |
| Snackbar            | ProgressSnackbar | snackbar_progress.xml |
| Partial layout      | -                | layout_user_info.xml  |
| Menu item           | -                | menu_home.xml         |

### View Ids:

| Tag                             | Id                         |
| ------------------------------- | -------------------------- | 
| \<fragment />                   | @+id/signInFragment        |
| \<FrameLayout /> etc.           | @+id/infoContainer         | 
| \<TextView />                   | @+id/currencyLabelTextView | 
| \<Button />                     | @+id/Button                | 
| \<TextInputLayout />            | @+id/emailInputLayout      | 
| \<TextInput /> or \<EditText /> | @+id/emailInput            | 
| \<ImageView />                  | @+id/likeImage             | 
| \<GradientView />               | @+id/gradientView          |

### Strings: 

| Text                             | Resource Name                                            |
| -------------------------------- | -------------------------------------------------------- |
| First Name (label)               | \<string name="first_name_label">My Artists\</string>    |
| Loading... (simple text)         | \<string name="loading">Loading…\</string>               |
| Total: 5 items (with formatting) | \<string name="total_pattern">Total: %1$d %2$s\</string> |
| Song / Songs (plural)            | \<plurals name="song_plural">...\</plurals>              |
| (string array)                   | \<string-array name="country_array">...\</string-array>  |

В случае `plurals` и `string-array` ресурсы необходимо выносить в отдельный файл `plurals.xml` и `string_arrays.xml` соответственно.

### Dimens: 

| Purpose              | Resource Name                                 |
| -------------------- | --------------------------------------------- |
| View width or height | \<dimen name="feed_item_height">45dp\</dimen>  |
| Text size            | \<dimen name="default_text_size">14sp\</dimen> |

В случае если высота и ширина элемента одинаковы необходимо использовать суффикс `_size`.

### Drawable:

| Type         | Resource Name                          |
| ------------ | -------------------------------------- |
| Background   | background_splash.webp                 |
| Icon         | ic_arrow_back_whit.xml                 |
| Simple image | image_app_logo.webp                    |
| Selector     | selector_white_to_black_text_color.xml |

### Colors: 

| Description       | Resource Name                                          |
| ----------------- | ------------------------------------------------------ |
| Simple color      | \<color name="colorWhite">#FFFFFFFF\</color>            |
| Translucent color | \<color name="colorWhiteTranslucent">#7FFFFFFF\</color> |

В случае использования одинаковых цветов с разной прозрачностью необходимо использовать суффикс с величиной прозрачности в десятичной системе, к примеру: 
`<color name="colorWhiteTranslucent50">#32FFFFFF</color>`

### Styles:

| Type  | Resource Name                                                         |
| ----- | --------------------------------------------------------------------- |
| Theme | \<style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar" /> |
| Style | \<style name="ToolbarStyle" />                                        |