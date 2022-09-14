# Native iPad Head Tracking


### Create a Switch
#### For Testing
Tapping anywhere on the screen will select the currently highlighted item
~~~
Tap Settings > Accessibility > Switch Control > Switches > Add New Switch > Screen > Full Screen > Select Item
~~~

### Enable Head Tracking
~~~
Settings > Accessibility > Switch Control > Head Tracking > On
~~~

> #### Actions
> ~~~
> Tap Raise Eyebrows > System = Tap
> ~~~
> *obviously pick what is best ( raise eyebrows was selected for demo purposes )*


### Start Default Switch Control
~~~
Tap Settings > Accessibility > Switch Control > Switch Control > On
~~~

> - This turns on the auto scanner ( blue outline, rotating through selections )
> - The auto scanner only stays active for about a minute
> - Tap anywhere on screen to restart scanning
> - **Triple tap home button to turn off Switch Control** ( must click home button 3 times in less than one second )



### Activate Head Tracking instead of default scanning
> - While auto scanner is scanning, tap anywhere on the screen to select an item.
>   - The first switch we created allows anywhere tap to select whatever is highlighted
> - When an item is selected we get several options
>   - Tap
>   - Scroll Down ( only visible on specific items )
>   - Scroll Right ( only visible on specific items )
>   - Two Dots ( at bottom ) to view additional options
> - Tap screen when two dots are selected for additional options
> - Tap screen when top row is selected
> - Tap screen when **Head Tracking** is highlighted

~~~
Triple click home button to Turn OFF head tracking
Triple click home button to Turn ON head tracking
~~~

---
**TESTED: SUCCESS**
- [x] 8th gen iPad with iPadOS 15.7
- [x] 9th gen iPad with iPadOS 15.3

**TESTED: FAILED**
- [x] 6th gen iPad with unknown iPadOS

---