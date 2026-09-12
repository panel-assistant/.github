# Panel Assistant

**Fast, dependable Android wall panels for Home Assistant, set up and managed from Home Assistant itself, whoever made them.**

Android wall panels are capable hardware let down by their software. Dashboards lag, taps go missing, the maker's own app pushes onto the screen, and every make needs a different app and a different routine to set up. Most people put up with it, because a panel with no buttons and no dependable reset is an expensive thing to break.

Panel Assistant is the free, open-source fix. It turns an Android wall panel into an appliance that runs your existing Home Assistant dashboards quickly and keeps running them, with one consistent way to set up and manage every panel you own.

- **Set up from Home Assistant.** Add a panel the way you add any other device: give it the panel's address, or plug a new panel into your computer and install from the browser.
- **Fast on modest hardware.** Your dashboard is rendered on the panel using only the data it actually shows, which is most of the difference between a panel that lags and one that responds straight away.
- **One system for every make.** Different makes and models look and behave the same from Home Assistant, without the maker's software in the way.
- **Know before you buy.** The supported panels list shows what works on each model before you spend the money.

**Start at [panel-assistant.io](https://panel-assistant.io)** for which panels are supported, how to get started, and how it all works.

## The projects

- **[Panel Assistant](https://github.com/panel-assistant/ha-integration)**: the Home Assistant integration, installed through HACS. It installs ha-paneld on your panels, connects them to Home Assistant and keeps them up to date.
- **[ha-paneld](https://github.com/maxlyth/ha-paneld)**: the app on each panel. It renders the dashboard, drives the panel's hardware and keeps the panel running on its own.
- **[panel-assistant.io](https://github.com/panel-assistant/panel-assistant.io)**: the website and documentation.

## Get involved

Panel Assistant is new and moving quickly, and supporting every panel worth mounting takes real hardware in real homes. Star [the integration](https://github.com/panel-assistant/ha-integration), report how your panel gets on in its [issues](https://github.com/panel-assistant/ha-integration/issues), or come and talk in the [Panel Assistant Discord](https://panel-assistant.io/go/discord).

Free and open source, with no account, no cloud and no subscription.
