# android-animate-RichEditor
android rich editor which enables users to insert/delete bitmaps and text into edit-view with animations.<br><br>
####target goal
Recently, my product manager asks us android developers to implement this kind of interactive experience: a rich editor which enables users to insert/delete images and text at any where they want. However, almost everyone denies this demand at first, because our time remain is	at tension and this kind of demand may cause unpredicted out-of-control.<br><br>
But for me, overcoming challenging difficulties makes me thrilling, and i enjoy it.  #(*^﹏^*)#
####compare with other rich editors
There exists other open-source rich editor projects in github, and i did run some of them.
##One project uses WebView + HTML, the inserted images looks so strange there.
##One project uses EditText + ImageSpan, maybe it's highly efficiency, but it's not that stable and robust.
##and so on..
However, most of them are uncomfortable and inconvenient.<br><br>
I implement this rich editor by using SrollView + LinearLayout. As you know, there may exist many views in this Editor, but you can never doubt that SrollView + LinearLayout could be quite smooth if you deal child-views reasonably. Besides, LinearLayout could add some special animations when adding/deleting child-views.
####captured images
<td>
	 <img src="capture01.gif" width="300" height="500" />
	 <img src="capture02.gif" width="300" height="500" />
</td>
####follow-ups
source code will be committed later.
####demo apk download
currently hold on.
####extras
later on, i will add some instructions for use the code.
