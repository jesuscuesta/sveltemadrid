<script>
  export let name;
</script>

<style>
  html {
    height: 100%;
    overflow: hidden;
  }

  body {
    height: 100%;
    overflow: auto;
    -webkit-overflow-scrolling: touch;
  }

  html {
    height: 100%;
    background: #ffffff
      url("https://images.unsplash.com/photo-1449168013943-3a15804bb41c?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&w=1080&fit=max&s=1958d4bfb59a246c6092ff0daabd284b")
      no-repeat center bottom fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }

  #cspio-page {
    background-color: rgba(0, 0, 0, 0);
  }

  .flexbox #cspio-page {
    align-items: center;
    justify-content: center;
  }

  .cspio body {
    background: transparent;
  }

  .cspio body,
  .cspio body p {
    font-family: Helvetica, Arial, sans-serif;
    font-weight: 400;

    font-size: 20px;
    line-height: 1.5em;
    color: #ffffff;
  }

  ::-webkit-input-placeholder {
    font-family: Helvetica, Arial, sans-serif;
    font-weight: 400;
  }

  ::-moz-placeholder {
    font-family: Helvetica, Arial, sans-serif;
    font-weight: 400;
  }

  :-ms-input-placeholder {
    font-family: Helvetica, Arial, sans-serif;
    font-weight: 400;
  }

  :-moz-placeholder {
    font-family: Helvetica, Arial, sans-serif;
    font-weight: 400;
  }

  .cspio h1,
  .cspio h2,
  .cspio h3,
  .cspio h4,
  .cspio h5,
  .cspio h6 {
    font-family: "Pacifico";
    color: #ffffff;
  }

  #cspio-headline {
    font-family: "Pacifico";
    font-weight: 400;

    font-size: 48px;
    color: #ffffff;
    line-height: 1em;
  }

  .cspio button {
    font-family: Helvetica, Arial, sans-serif;
    font-weight: 400;
  }

  .cspio a,
  .cspio a:visited,
  .cspio a:hover,
  .cspio a:active {
    color: #ffffff;
  }

  #cspio-socialprofiles a {
    color: #ffffff;
  }
  .cspio .btn-primary,
  .cspio .btn-primary:focus,
  .gform_button,
  #mc-embedded-subscribe,
  .submit-button {
    color: black;
    text-shadow: 0 -1px 0 rgba(255, 255, 255, 0.3);
    background-color: #ffffff;
    background-image: -moz-linear-gradient(top, #ffffff, #d9d9d9);
    background-image: -ms-linear-gradient(top, #ffffff, #d9d9d9);
    background-image: -webkit-gradient(
      linear,
      0 0,
      0 100%,
      from(#ffffff),
      to(#d9d9d9)
    );
    background-image: -webkit-linear-gradient(top, #ffffff, #d9d9d9);
    background-image: -o-linear-gradient(top, #ffffff, #d9d9d9);
    background-image: linear-gradient(top, #ffffff, #d9d9d9);
    background-repeat: repeat-x;
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffff', endColorstr='#d9d9d9', GradientType=0);
    border-color: #d9d9d9 #d9d9d9 #b3b3b3;
    border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
    *background-color: #d9d9d9;
    filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  }

  .cspio .btn-primary:hover,
  .cspio .btn-primary:active,
  .cspio .btn-primary.active,
  .cspio .btn-primary.disabled,
  .cspio .btn-primary[disabled],
  .cspio .btn-primary:focus:hover,
  .cspio .btn-primary:focus:active,
  .cspio .btn-primary:focus.active,
  .cspio .btn-primary:focus.disabled,
  .cspio .btn-primary:focus[disabled],
  #mc-embedded-subscribe:hover,
  #mc-embedded-subscribe:active,
  #mc-embedded-subscribe.active,
  #mc-embedded-subscribe.disabled,
  #mc-embedded-subscribe[disabled] {
    background-color: #d9d9d9;
    *background-color: #cccccc;
  }

  .cspio .btn-primary:active,
  .cspio .btn-primary.active,
  .cspio .btn-primary:focus:active,
  .cspio .btn-primary:focus.active,
  .gform_button:active,
  .gform_button.active,
  #mc-embedded-subscribe:active,
  #mc-embedded-subscribe.active {
    background-color: #bfbfbf;
  }

  .form-control,
  .progress {
    background-color: rgba(255, 255, 255, 0.85);
  }

  #cspio-progressbar span,
  .countdown_section {
    color: black;
    text-shadow: 0 -1px 0 rgba(255, 255, 255, 0.3);
  }

  .cspio .btn-primary:hover,
  .cspio .btn-primary:active {
    color: black;
    text-shadow: 0 -1px 0 rgba(255, 255, 255, 0.3);
    border-color: #e6e6e6;
  }

  .cspio input[type="text"]:focus {
    webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075),
      0 0 8px rgba(217, 217, 217, 0.6);
    -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075),
      0 0 8px rgba(217, 217, 217, 0.6);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075),
      0 0 8px rgba(217, 217, 217, 0.6);
  }

  #cspio-content {
    max-width: 600px;
    background-color: #000000;
    -webkit-border-radius: 2px;
    border-radius: 2px;
    -moz-background-clip: padding;
    -webkit-background-clip: padding-box;
    background-clip: padding-box;
    background-color: transparent;
  }

  .cspio .progress-bar,
  .countdown_section,
  .cspio .btn-primary,
  .cspio .btn-primary:focus,
  .gform_button {
    background-image: none;
    text-shadow: none;
  }

  .cspio input,
  .cspio input:focus {
    -webkit-box-shadow: none !important;
    box-shadow: none !important;
  }

  #cspio-page {
    background: -moz-radial-gradient(
      ellipse at center,
      rgba(0, 0, 0, 0.3) 0%,
      rgba(0, 0, 0, 0.2) 37%,
      rgba(0, 0, 0, 0) 68%,
      rgba(0, 0, 0, 0) 100%
    );
    background: -webkit-radial-gradient(
      ellipse at center,
      rgba(0, 0, 0, 0.3) 0%,
      rgba(0, 0, 0, 0.2) 37%,
      rgba(0, 0, 0, 0) 68%,
      rgba(0, 0, 0, 0) 100%
    );
    background: radial-gradient(
      ellipse at center,
      rgba(0, 0, 0, 0.3) 0%,
      rgba(0, 0, 0, 0.2) 37%,
      rgba(0, 0, 0, 0) 68%,
      rgba(0, 0, 0, 0) 100%
    );
  }

  .cspio body {
    background: -moz-radial-gradient(
      center,
      ellipse cover,
      rgba(0, 0, 0, 0) 7%,
      rgba(0, 0, 0, 0) 80%,
      rgba(0, 0, 0, 0.23) 100%
    );
    background: -webkit-radial-gradient(
      center,
      ellipse cover,
      rgba(0, 0, 0, 0) 7%,
      rgba(0, 0, 0, 0) 80%,
      rgba(0, 0, 0, 0.23) 100%
    );
    background: radial-gradient(
      ellipse at center,
      rgba(0, 0, 0, 0) 7%,
      rgba(0, 0, 0, 0) 80%,
      rgba(0, 0, 0, 0.23) 100%
    );
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#00000000', endColorstr='#3b000000',GradientType=1 );
  }

  #cspio-subscribe-btn {
    background: transparent;
    border: 1px solid #fff !important;
    color: #fff;
  }

  #cspio-subscribe-btn:hover {
    background: rgba(255, 255, 255, 0.2);
    color: #fff;
  }

  #cspio-credit img {
    margin-left: auto;
    margin-right: auto;
    width: 125px;
    margin-top: -4px;
  }

  #cspio-credit {
    font-size: 11px;
  }

  .cspio .input-group-btn,
  .cspio .input-group {
    display: block;
    width: 100%;
  }
  .cspio #cspio-subscribe-btn {
    margin-left: 0;
    width: 100%;
    display: block;
  }
  .cspio .input-group .form-control:first-child,
  .cspio .input-group-addon:first-child,
  .cspio .input-group-btn:first-child > .btn,
  .cspio .input-group-btn:first-child > .dropdown-toggle,
  .cspio
    .input-group-btn:last-child
    > .btn:not(:last-child):not(.dropdown-toggle) {
    border-bottom-right-radius: 4px;
    border-top-right-radius: 4px;
  }
  .cspio .input-group .form-control:last-child,
  .cspio .input-group-addon:last-child,
  .cspio .input-group-btn:last-child > .btn,
  .cspio .input-group-btn:last-child > .dropdown-toggle,
  .cspio .input-group-btn:first-child > .btn:not(:first-child) {
    border-bottom-left-radius: 4px;
    border-top-left-radius: 4px;
  }

  #cspio-privacy-policy-txt {color: #ffffff; }
</style>

<div id="cspio-page">
  <div id="cspio-content">

    <h1 id="cspio-headline">Svelte Madrid</h1>

    <h2 id="cspio-headline">En Construcción</h2>

    <div id="cspio-description">
      ¡En unas semanas tendremos toda la web en funcionamiento!
    </div>

    <form id="cspio-form" action="" method="post">
      <div id="cspio-field-wrapper">
        <div class="row">
          <div class="col-md-12 seperate">
            <div class="input-group">
              <!-- Begin Mailchimp Signup Form -->
              <link
                href="//cdn-images.mailchimp.com/embedcode/classic-10_7.css"
                rel="stylesheet"
                type="text/css" />
              <style type="text/css">
                #mc_embed_signup {
                  background: #fff;
                  clear: left;
                  font: 14px Helvetica, Arial, sans-serif;
                }
                /* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
              </style>
              <div id="mc_embed_signup">
                <form
                  action="https://gmail.us20.list-manage.com/subscribe/post?u=2efe0c4b70ac73c297f16921c&amp;id=5f5dbb8d24"
                  method="post"
                  id="mc-embedded-subscribe-form"
                  name="mc-embedded-subscribe-form"
                  class="validate"
                  target="_blank"
                  novalidate>
                  <div id="mc_embed_signup_scroll">
                    <h2>Subscríbete para recibir más información sobre SvelteJS</h2>
                    <div class="indicates-required">
                      <span class="asterisk">*</span>
                      obligatorio
                    </div>
                    <div class="mc-field-group">
                      <label for="mce-EMAIL">
                        Email
                        <span class="asterisk">*</span>
                      </label>
                      <input
                        type="email"
                        value=""
                        name="EMAIL"
                        class="required email"
                        id="mce-EMAIL" />
                    </div>
                    <div class="mc-field-group">
                      <label for="mce-FNAME">Nombre</label>
                      <input
                        type="text"
                        value=""
                        name="FNAME"
                        class=""
                        id="mce-FNAME" />
                    </div>
                    <div id="mce-responses" class="clear">
                      <div
                        class="response"
                        id="mce-error-response"
                        style="display:none" />
                      <div
                        class="response"
                        id="mce-success-response"
                        style="display:none" />
                    </div>
                    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
                    <div
                      style="position: absolute; left: -5000px;"
                      aria-hidden="true">
                      <input
                        type="text"
                        name="b_2efe0c4b70ac73c297f16921c_5f5dbb8d24"
                        tabindex="-1"
                        value="" />
                    </div>
                    <div class="clear">
                      <input
					  	style="color:#000000"
                        type="submit"
                        value="Subscríbete"
                        name="subscribe"
                        id="mc-embedded-subscribe"
                        class="button btn btn-lg btn-primary form-el noglow" />
                    </div>
                  </div>
                </form>
              </div>
              <script
                type="text/javascript"
                src="//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js">

              </script>
              <script type="text/javascript">
                (function($) {
                  window.fnames = new Array();
                  window.ftypes = new Array();
                  fnames[0] = "EMAIL";
                  ftypes[0] = "email";
                  fnames[1] = "FNAME";
                  ftypes[1] = "text";
                })(jQuery);
                var $mcj = jQuery.noConflict(true);
              </script>
              <!--End mc_embed_signup-->
  
        
            </div>
          </div>
        </div>
      </div>
    </form>

    <span id="cspio-privacy-policy-txt">We promise to never spam you.</span>

    <div id="cspio-socialprofiles">
      <a href="http://www.svelte.es" target="_blank">
        <i class="fa fa-wordpress fa-2x" />
      </a>
      <a href="https://twitter.com/sveltemadrid" target="_blank">
        <i class="fa fa-twitter fa-2x" />
      </a>
      <a href="mailto:" target="sveltemadrid@gmail.com">
        <i class="fa fa-envelope fa-2x" />
      </a>
    </div>

  </div>
  <!-- end of #cspio-content -->
</div>
