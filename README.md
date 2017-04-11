# android-animate-RichEditor
android rich editor which enables users to insert/delete bitmaps and text into edit-view with animations.
#### target goal
Recently, my product manager requires our team to implement this kind of interactive experience: a rich editor which enables users to insert/delete images and text at anywhere they want. However, almost everyone denies this demand at first, because our time remain is at tension and this kind of demand may cause unpredicted out-of-control.<br>
However, overcoming challenging difficulties is thrilling, isn't it?
#### compare with other rich editors
There exists other open-source rich editor projects in github, and i did run some of them.    
* One project uses WebView + HTML, the inserted images looks so strange there.
* One project uses EditText + ImageSpan, maybe it's highly efficiency, but it's not that stable and robust.
* and so on..

However, most of them are uncomfortable and inconvenient.<br>
I implement this rich editor by using SrollView + LinearLayout. As you know, there may exist many views in this Editor, but you can never doubt that SrollView + LinearLayout could be quite smooth if you deal child-views reasonably. <br>
Besides, LinearLayout could add some special animations when adding/deleting child-views.
#### captured images
<td>
	 <img src="capture01.gif" width="300" height="500" />
	 <img src="capture02.gif" width="300" height="500" />
</td>

#### demo apk download
[apk download](RichEditor.apk) (right in this github project)

#### extras
later on, i will add some instructions for use the code.

### Version: 1.0

  * Pilot version

## License

    Copyright 2015, xmuSistone

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

