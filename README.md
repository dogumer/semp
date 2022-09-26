# semp (Selenium-Made-Simple)
Semp is a markup language for selenium library which makes web manipulation easier and faster!

## Advantages of semp:
- Easy to understand
- Faster coding (no worries about syntax)
- Create web bots easier
- External .semp files
- Directly start from terminal

## How To Use:
browser / starts browser (browser used in line 1 is not in loop) \
goto *webaddress / go to website \
findelement (options: byname, byid, byxpath, bycssselector) *argument / find element by it's properties \
sendkeys *keys / send keys to element\
clearelement / clear element \
clickelement / click element \
submitelement / submit element \
doubleclickelement / Double-click element \
scroll *xcoordinate *ycoordinate / scroll to specified coordinate \
scroll toelement / scroll to selected element \
alert (options: accept, dismiss) / Accept or dismiss alert pop-up \
getscreenshot *filesource / Save screenshot of full-page \
quit / quit browser \
killbrowser/ kill browser \
quitsemp / quit semp \
sleep *second / waiting time until next process starts \
browser / starts browser again after quiting (used other than 1st line)

## Example .semp files:
[Example 1]()
[Example 2]()

## Libraries used in semp
[SeleniumHQ](https://github.com/SeleniumHQ) - [Selenium](https://github.com/SeleniumHQ/selenium) \
[Boni Garcia](https://github.com/bonigarcia/) - [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)
