### How to add to your MAL

Navigate to [Custom Styles](http://myanimelist.net/editprofile.php?go=stylepref&do=cssadv) on your anime list profile.

In the `Advanced CSS File` field include the three css and a Color found in css/Material/Colors

```css
/* Base */
@import "https://0x9ae76c.github.io/MAL/css/BAR.css";
@import "https://0x9ae76c.github.io/MAL/css/MAL.css";
@import "https://googledrive.com/host/0BxjwQr0BBXs-aDYxM2JlaFM2bnM";

/* Color */
@import "https://0x9ae76c.github.io/MAL/css/Material/Colors/Red.css";

/* General Normalization */
* { text-decoration: none !important; }

/* Uncomment following for custom background */
/*
:root {
  background-image: url('YOUR_IMAGE_URL');
  background-size: cover;
}
*/
```