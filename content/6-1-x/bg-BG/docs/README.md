# Официално ръководство

Преди да продължите да четете, уверете се че версията на документа съвпада с версията на Electron от която се интересувате. Версията може да бъде намерена в URL адреса на страницата. Ако не успявате да идентифицирате версията, то най-вероятно четете настоящият документ касаещ версия на продукта която се разработва в момента. Бъдете внимателни защото информацията, която получавате в момента може да не е съвместима с версията на Electron, с която работите в момента. Ако се интересувате от по-стара версия на продукта, ви съветваме да използвате функцията [browse by tag](https://github.com/electron/electron/tree/v1.4.0) в GitHub като отворите менюто "Switch branches/tags" и изберете версията, която ви интересува.

## Често задавани въпроси

There are questions that are asked quite often. Check this out before creating an issue:

* [често задавани въпроси за Electron](faq.md)

## Ръководства и уроци

* [Създаване на среда за разработка](tutorial/development-environment.md)
  * [Настройване при macOS](tutorial/development-environment.md#setting-up-macos)
  * [Настройване при Windows](tutorial/development-environment.md#setting-up-windows)
  * [Настройване при Linux](tutorial/development-environment.md#setting-up-linux)
  * [Избор на редактор](tutorial/development-environment.md#a-good-editor)
* [Създаване на вашето първо приложение](tutorial/first-app.md)
  * [Инсталиране на Електрон](tutorial/first-app.md#installing-electron)
  * [Същност при разработка с Електрон](tutorial/first-app.md#electron-development-in-a-nutshell)
  * [Работа на вашето приложение](tutorial/first-app.md#running-your-app)
* [Шаблони и CLI](tutorial/boilerplates-and-clis.md)
  * [Шаблон срещу CLI](tutorial/boilerplates-and-clis.md#boilerplate-vs-cli)
  * [electron-forge](tutorial/boilerplates-and-clis.md#electron-forge)
  * [electron-builder](tutorial/boilerplates-and-clis.md#electron-builder)
  * [electron-react-boilerplate](tutorial/boilerplates-and-clis.md#electron-react-boilerplate)
  * [Други инструменти и шаблони](tutorial/boilerplates-and-clis.md#other-tools-and-boilerplates)
* [Архитектура на приложението](tutorial/application-architecture.md)
  * [Основен и Рендериращ процес](tutorial/application-architecture.md#main-and-renderer-processes)
  * [Използване на API на Електрон](tutorial/application-architecture.md#using-electron-apis)
  * [Използване на Node.js API](tutorial/application-architecture.md#using-nodejs-apis)
  * [Използване на родни Node.js модули](tutorial/using-native-node-modules.md)
* Добавяне на функции към вашето приложение
  * [Известия](tutorial/notifications.md)
  * [Последни документи](tutorial/desktop-environment-integration.md#recent-documents)
  * [Прогрес на приложението](tutorial/progress-bar.md)
  * [Потребителско док меню](tutorial/macos-dock.md)
  * [Потребителска Windows лентата на задачите](tutorial/windows-taskbar.md)
  * [Потребителски настолни действия при Linux](tutorial/linux-desktop-actions.md)
  * [Клавишни комбинации](tutorial/keyboard-shortcuts.md)
  * [Offline/Online откриване](tutorial/online-offline-events.md)
  * [Представляващ файл за macOS BrowserWindows](tutorial/represented-file.md)
  * [Роден Drag & Drop файл](tutorial/native-file-drag-drop.md)
* [Accessibility](tutorial/accessibility.md)
  * [Spectron](tutorial/accessibility.md#spectron)
  * [Devtron](tutorial/accessibility.md#devtron)
  * [Разрешаване на достъпността](tutorial/accessibility.md#enabling-accessibility)
* [5256783105227699](tutorial/application-debugging.md)
  * [Отстраняване на грешк](tutorial/debugging-main-process.md)
  * [Работа със Selenium и Web Driver](tutorial/using-selenium-and-webdriver.md)
  * [Тестване и употреба на Системи за непрекъсната интеграция (Travis, Jenkins)](tutorial/testing-on-headless-ci.md)
  * [Разширения за работа с инструменти за писане на програмен код](tutorial/devtools-extension.md)
  * [5256783105227699](tutorial/automated-testing-with-a-custom-driver.md)
* Packaging
  * [5256783105227699](tutorial/code-signing.md)
* [Разпределения](tutorial/application-distribution.md)
  * [Support](tutorial/support.md)
  * [Mac App Store](tutorial/mac-app-store-submission-guide.md)
  * [Windows Store](tutorial/windows-store-guide.md)
  * [Snapcraft](tutorial/snapcraft.md)
* [Сигурност](tutorial/security.md)
  * [Докладване на проблеми със сигурността](tutorial/security.md#reporting-security-issues)
  * [Проблеми със сигурността и обновяване на Chromium](tutorial/security.md#chromium-security-issues-and-upgrades)
  * [Electron Security Warnings](tutorial/security.md#electron-security-warnings)
  * [Списък за сигурност](tutorial/security.md#checklist-security-recommendations)
* [5256783105227699](tutorial/updates.md)
  * [Deploying an Update Server](tutorial/updates.md#deploying-an-update-server)
  * [Добавяне на новости във вашето приложение](tutorial/updates.md#implementing-updates-in-your-app)
  * [Прилагане на новости](tutorial/updates.md#applying-updates)

## รายละเอียดบทความสอน

บทความสอนแต่ละบทจะขยายความจากหัวข้อคำแนะนำข้างบน.

* [Инсталиране на Електрон в детайли](tutorial/installation.md)
  * [Proxies](tutorial/installation.md#proxies)
  * [Потребителски mirrors и кеширане](tutorial/installation.md#custom-mirrors-and-caches)
  * [Отстраняване на неизправности](tutorial/installation.md#troubleshooting)
* [Схема на версиите в детайли](tutorial/electron-versioning.md)
  * [semver](tutorial/electron-versioning.md#semver)
  * [Стабилни клонове](tutorial/electron-versioning.md#stabilization-branches)
  * [Бета версии и поправка на bug-ове](tutorial/electron-versioning.md#beta-releases-and-bug-fixes)
* [В детайли: Пакетиране на кода на приложението с asar](tutorial/application-packaging.md)
  * [การสร้างคลังเก็บอาซาร์](tutorial/application-packaging.md#generating-asar-archives)
  * [การใช้ asar Archives](tutorial/application-packaging.md#using-asar-archives)
  * [Ограничения](tutorial/application-packaging.md#limitations-of-the-node-api)
  * [การเพิ่มไฟล์ที่คลายการบีบอัดไปยัง asar Archives](tutorial/application-packaging.md#adding-unpacked-files-to-asar-archives)
* [In Detail: Testing Widevine CDM](tutorial/testing-widevine-cdm.md)
* [Използване на Pepper Flash Plugin в детайли](tutorial/using-pepper-flash-plugin.md)
* [Рендиране извън екрана](tutorial/offscreen-rendering.md)

---

* [Речник на термините](glossary.md)

## Функционална документация

* [บทย่อ](api/synopsis.md)
* [กระบวนการของวัตถุ](api/process.md)
* [Поддържани превключващи команди на Chrome](api/chrome-command-line-switches.md)
* [ตัวแปรสภาพแวดล้อม](api/environment-variables.md)
* [5256783105227699](api/breaking-changes.md)

### Персонални DOM елементи:

* [Обект `File`](api/file-object.md)
* [`<webview>`Етикет](api/webview-tag.md)
* [Функция `window.open`](api/window-open.md)

### Модули за основния процес:

* [app](api/app.md)
* [autoUpdater](api/auto-updater.md)
* [BrowserView](api/browser-view.md)
* [BrowserWindow](api/browser-window.md)
* [contentTracing](api/content-tracing.md)
* [dialog](api/dialog.md)
* [globalShortcut](api/global-shortcut.md)
* [inAppPurchase](api/in-app-purchase.md)
* [ipcMain](api/ipc-main.md)
* [Menu](api/menu.md)
* [MenuItem](api/menu-item.md)
* [net](api/net.md)
* [5256783105227699](api/net-log.md)
* [powerMonitor](api/power-monitor.md)
* [powerSaveBlocker](api/power-save-blocker.md)
* [protocol](api/protocol.md)
* [session](api/session.md)
* [systemPreferences](api/system-preferences.md)
* [Tray](api/tray.md)
* [webContents](api/web-contents.md)

### Модули за визуализиращи процеси (Web страници):

* [desktopCapturer](api/desktop-capturer.md)
* [ipcRenderer](api/ipc-renderer.md)
* [remote](api/remote.md)
* [webFrame](api/web-frame.md)

### Общи модули:

* [clipboard](api/clipboard.md)
* [crashReporter](api/crash-reporter.md)
* [nativeImage](api/native-image.md)
* [screen](api/screen.md)
* [shell](api/shell.md)

## Разработка

See [development/README.md](development/README.md)
