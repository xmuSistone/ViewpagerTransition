# android-page-transition
viewpager with vertical sliding effects and activity transition<br>
<img src="capture1.jpg" width="540" height="960" /> <br>
The original design is:  [here](https://dribbble.com/shots/2493845-ToFind-Transition-Test)<br>
####Captured images:
<td>
         <img src="gif1.gif" width="290" height="515" />
	 <img src="gif2.gif" width="290" height="515" />
	 <img src="gif3.gif" width="290" height="515" />
</td>

####Coding design
Sliding pages to the left or right, as we know, could be implemented by using ViewPager. And fortunately, ViewPager's PagerTransformer is allowed for customization. That's to say, [CustPagerTransformer](android-page-transition/app/src/main/java/com/stone/transition/CustPagerTransformer.java) could get rid of all the parallax effects. <br>
Then, in viewpager's fragment item, vertical slide is an independent module, which could be realized by using ViewDragHelper. In the activity transition part, android OS (above 5.0) makes it easy to transfer to another activity. <br>

####Thanks
[rubensousa/ViewPagerCards](https://github.com/rubensousa/ViewPagerCards)<br>
[antoniolg/MaterialEverywhere](https://github.com/antoniolg/MaterialEverywhere)

####Demo Apk
[download](https://github.com/xmuSistone/android-page-transition/blob/master/pageTransition.apk?raw=true)

### Version: 1.0

  * Pilot version

## License

    Copyright 2016, xmuSistone

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
