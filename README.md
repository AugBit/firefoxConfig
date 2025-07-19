# firefoxConfig
config to make firefox look better

type about:config in search bar

search toolkit.legacyUserProfileCustomizations.stylesheets and set to true

go to about:profiles and open root directory

create a folder called chrome

add a file called userChrome.css

add to file and save

:root {
  --tabs-navbar-separator-color: rgba(0, 0, 0, 0) !important;
}
@namespace url("http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul");
#back-button, #forward-button { display: none !important; }

reboot firefox
