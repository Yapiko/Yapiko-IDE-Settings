# Eclipse settings

## Pre requirements

You need to have installed **Eclipse** on your computer. And *if you want*, **updated to the latest version**. We strongly recommend updating to the latest version to **avoid settings conflicts**.

### Settings installation

Go `File > Import > General > Preferences` and browse to `YapikoSettings.epf` settings file. Done!

### Formatter installation

Go to `Eclipse > Preferences` or press `CMD + ","`. Then, go to `Java > Code style > Formatter` if you already have `Yapiko Style` selected don't do nothing more, if not, click the button `Import` and browse the `YapikoFormatter.xml` file. Done!

### CheckStyle installation

You can install CheckStyle just [Dragging me to your eclipse workspace](http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=150). Just drag the latest link **on a non-text area**. For example, the top navigation bar.

Then, you have to set the correct configuration file. You can do it going to `Eclipse > Preferences` or `CMD + ","`. Then `Checkstyle` tab and click the `New` button.

On `Type` select `External configuration File`, type the `Name` you want for this configuration and browse to the `YapikoCheckStyle.xml` file.

The last you have to do is setting the Yapiko settings as default, selecting the added settings and clicking the `Set as default` button. Done!

Installation site: [https://marketplace.eclipse.org/content/checkstyle-plug](https://marketplace.eclipse.org/content/checkstyle-plug)

### Lombok installation

Launch lombok installer with `java -jar lombok-path.jar` with Eclipse IDE closed. Then, you have to perform an Project clean, to do it, open Eclipse and go to `Project > Clean...` and continue with the dialog. Done!

You can download the latest version here: [https://projectlombok.org/download](https://projectlombok.org/download)

### SonarLint installation

You can install SonarLint just [Dragging me to your eclipse workspace](http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=2568658). Just drag the latest link **on a non-text area**. For example, the top navigation bar.

Installation site: [https://marketplace.eclipse.org/content/sonarlint](https://marketplace.eclipse.org/content/sonarlint)