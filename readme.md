# stylus-eos-forum-dark

Darker theme for the EndeavourOS forum, via Stylus.

<details>
      <summary>Screenshot before</summary>

![Before](/assets/before.png)

</details>

<details>
      <summary>Screenshot after</summary>

![After](/assets/after.png)

</details>

## How to use

If you haven't already, you'll need to install the `Stylus` browser extension.

After that, in Stylus, you can create a new "Style" and copy/paste the css below

<details>
      <summary>CSS</summary>

        ```css
        @-moz-document domain("forum.endeavouros.com") {

            :root {
                --scheme-type: dark;
                --primary: #fff;
                --secondary: #141414;
                --tertiary: #9081bb;
                --quaternary: #b2afcf;
                --header_background: #1e1e1e;
                --header_primary: #fafafa;
                --highlight: #fafafa;
                --danger: #e45735;
                --success: #090;
                --love: #fa6c8d;
                --always-black-rgb: 0, 0, 0;
                --primary-rgb: 250, 250, 250;
                --primary-low-rgb: 55.0, 55.0, 55.0;
                --primary-very-low-rgb: 45.0, 45.0, 45.0;
                --secondary-rgb: 42, 40, 40;
                --header_background-rgb: 83, 80, 80;
                --tertiary-rgb: 144, 129, 187;
                --primary-very-low: #1e1e1e;
                --primary-low: #373737;
                --primary-low-mid: #8a8a8a;
                --primary-medium: #a3a3a3;
                --primary-high: #bcbcbc;
                --primary-very-high: #e1e1e1;
                --primary-50: #2d2d2d;
                --primary-100: #323232;
                --primary-200: #373737;
                --primary-300: #646464;
                --primary-400: #8a8a8a;
                --primary-500: #969696;
                --primary-600: #a3a3a3;
                --primary-700: #afafaf;
                --primary-800: #bcbcbc;
                --primary-900: #e1e1e1;
                --header_primary-low: #706e6e;
                --header_primary-low-mid: #a2a1a1;
                --header_primary-medium: #c2c1c1;
                --header_primary-high: #d6d6d6;
                --header_primary-very-high: #efefef;
                --secondary-low: #c0bdbd;
                --secondary-medium: #979191;
                --secondary-high: #6c6767;
                --secondary-very-high: #393737;
                --tertiary-very-low: #221c33;
                --tertiary-low: #2f2748;
                --tertiary-medium: #4a3d71;
                --tertiary-high: #65539a;
                --tertiary-hover: #a69ac9;
                --tertiary-50: #221c33;
                --tertiary-100: #261f39;
                --tertiary-200: #2a2240;
                --tertiary-300: #2f2748;
                --tertiary-400: #392f56;
                --tertiary-500: #413563;
                --tertiary-600: #4a3d71;
                --tertiary-700: #54457f;
                --tertiary-800: #5d4c8e;
                --tertiary-900: #65539a;
                --quaternary-low: #2e2b48;
                --highlight-low: #323232;
                --highlight-medium: #717171;
                --highlight-high: #e1e1e1;
                --danger-low: #591b0c;
                --danger-low-mid: rgba(99, 30, 13, 0.7);
                --danger-medium: #a13116;
                --danger-hover: #c63c1b;
                --success-low: #003d00;
                --success-medium: #005c00;
                --success-hover: #007a00;
                --love-low: #8a0524;
                --wiki: green;
                --blend-primary-secondary-5: #454444;
                --primary-med-or-secondary-med: #979191;
                --primary-med-or-secondary-high: #6c6767;
                --primary-high-or-secondary-low: #c0bdbd;
                --primary-low-mid-or-secondary-high: #6c6767;
                --primary-low-mid-or-secondary-low: #c0bdbd;
                --primary-or-primary-low-mid: #8a8a8a;
                --highlight-low-or-medium: #717171;
                --tertiary-or-tertiary-low: #2f2748;
                --tertiary-low-or-tertiary-high: #65539a;
                --tertiary-med-or-tertiary: #9081bb;
                --secondary-or-primary: #fafafa;
                --tertiary-or-white: #fff;
                --facebook-or-white: #fff;
                --twitter-or-white: #fff;
                --hljs-comment: #bba;
                --hljs-number: #aff;
                --hljs-string: #f99;
                --hljs-literal: #9ae;
                --hljs-tag: #99f;
                --hljs-attribute: #0ee;
                --hljs-symbol: #fbe;
                --hljs-bg: #333;
                --hljs-builtin-name: #a69ac9;
                --google: #fff;
                --google-hover: #f2f2f2;
                --instagram: #e1306c;
                --instagram-hover: #ac194b;
                --facebook: #1877f2;
                --facebook-hover: #0a54b3;
                --cas: #70ba61;
                --twitter: #1da1f2;
                --twitter-hover: #0c85d0;
                --github: #100e0f;
                --github-hover: #463e42;
                --discord: #7289da;
                --discord-hover: #4a67cf;
                --gold: #e7c300;
                --silver: silver;
                --bronze: #cd7f32;
            }
            .primary-textual {
                background-color: #141414;
            }

            .user-main .about .controls {
                background-color: #141414;
            }
            .user-main .about .details .user-profile-avatar {
                background-color: #141414;
            }
            .user-main .about .secondary {
                background-color: #141414;
            }

            .badge-card {
                background-color: #0f0f0f;
            }
            .alert.alert-info.clickable {
                margin-top: -10px;
            }

        }
        ```

</details>
