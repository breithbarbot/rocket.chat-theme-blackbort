# Blackbort-RocketChat
> Custom theme for Rocket Chat

<br>

## Visual

![Capture Blackbort RocketChat theme](capture-blackbort-rocketchat-theme.jpg "Capture Blackbort RocketChat theme")

<br>

## Usage

* Administration > Layout > Color :
    * Content Background Color : **#2A2A2A** | **color**
    * Primary Background Color : **#242425** | **color**
    * Primary Font Color : **#888889** | **color**
    * Primary Action Color : **#13679A** | **color**
    * Secondary Background Color : **#242425** | **color**
    * Secondary Font Color : **#A0A0A0** | **color**
    * Secondary Action Color : **#DDDDDD** | **color**
    * Component Color : **#3D3D3E** | **color**
    * Success Color : **#095C2C** | **color**
    * Pending Color : **#BF360C** | **color**
    * Error Color : **#870D0D** | **color**
    * Selection Color : **#0D4987** | **color**
    * theme-color-attention-color : **#9C27B0** | **color**

* Administration > Layout > Custom CSS :
    * ```css
      * {
          border-radius: 0 !important;
      }
      
      .message .reactions > li.selected {
          border-color: #3D3D3E;
          background-color: #242425;
      }
      
      .message .reactions > li {
          border-color: #000;
          background-color: #242425;
      }
      
      .code-colors {
          background-color: #333334;
          border-color: #333334;
          color: #FFF;
      }
      
      .side-nav .footer {
          background: url(/assets/logo) 50% no-repeat;
          background-size: cover;
      }
      
      .hljs {
          background: #333334 !important;
          color: #6F6F6F !important;
      }
      
      .hljs-keyword, .hljs-selector-tag, .hljs-subst {
          color: #6F6F6F;
      }
      
      .message-form .message-buttons:hover {
          background-color: #1D1D1F;
      }
      
      .page-settings .section {
          border: 1px solid #3D3D3E;
          background-color: #282828;
      }
      
      .page-settings .section-content .input-line {
          border-bottom: 1px solid #3D3D3E;
      }
      
      .message-form .message-form-text.editing {
          background-color: #222222;
      }
      
      .background-info-font-color {
          background-color: #0D4987;
      }
      ```

Enjoy!

<br>

## License

[MIT](LICENSE)