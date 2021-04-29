# Selenium Hints (java)


## Scroll to element

```
((JavascriptExecutor) webDriver).executeScript("arguments[0].scrollTop= 0",webDriver.findElement(By.cssSelector("")));
```

## Hover over element
```
new Actions(webDriver).moveToElement(webDriver.findElement(By.cssSelector("")));
```

## Switch to frame(element)
```
webDriver.switchTo().frame(webDriver.findElement(By.cssSelector(""));
```

## Switch to frame(parent)
```
webDriver.switchTo().parentFrame();
```

## Scroll by 
The window.scrollBy(x-coord, y-coord) method scrolls the document in the window by the given amount.
```
((JavascriptExecutor) webDriver).executeScript("window.scrollBy(0,100)");
```
