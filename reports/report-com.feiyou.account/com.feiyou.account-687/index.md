title: com.feiyou.account

# com.feiyou.account

[Google Play Store](https://play.google.com/store/apps/details?id=com.feiyou.account)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to read from field 'int com.feiyou.account.ui.fragment.MineFragment$2$ItemRecod.height' on a null object reference
// 	at com.feiyou.account.ui.fragment.MineFragment$2.getScrollY(MineFragment.java)
// 	at com.feiyou.account.ui.fragment.MineFragment$2.onScroll(MineFragment.java)
// 	at android.widget.AbsListView.invokeOnItemScrollListener(AbsListView.java:1463)
// 	at android.widget.ListView.layoutChildren(ListView.java:1813)
// 	at android.widget.AbsListView.onLayout(AbsListView.java:2148)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.FrameLayout.layoutChildren(FrameLayout.java:336)
// 	at android.widget.FrameLayout.onLayout(FrameLayout.java:273)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.RelativeLayout.onLayout(RelativeLayout.java:1079)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.FrameLayout.layoutChildren(FrameLayout.java:336)
// 	at android.widget.FrameLayout.onLayout(FrameLayout.java:273)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.LinearLayout.setChildFrame(LinearLayout.java:1743)
// 	at android.widget.LinearLayout.layoutVertical(LinearLayout.java:1586)
// 	at android.widget.LinearLayout.onLayout(LinearLayout.java:1495)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.FrameLayout.layoutChildren(FrameLayout.java:336)
// 	at android.widget.FrameLayout.onLayout(FrameLayout.java:273)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.FrameLayout.layoutChildren(FrameLayout.java:336)
// 	at android.widget.FrameLayout.onLayout(FrameLayout.java:273)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.LinearLayout.setChildFrame(LinearLayout.java:1743)
// 	at android.widget.LinearLayout.layoutVertical(LinearLayout.java:1586)
// 	at android.widget.LinearLayout.onLayout(LinearLayout.java:1495)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.widget.FrameLayout.layoutChildren(FrameLayout.java:336)
// 	at android.widget.FrameLayout.onLayout(FrameLayout.java:273)
// 	at com.android.internal.policy.PhoneWindow$DecorView.onLayout(PhoneWindow.java:2678)
// 	at android.view.View.layout(View.java:16636)
// 	at android.view.ViewGroup.layout(ViewGroup.java:5437)
// 	at android.view.ViewRootImpl.performLayout(ViewRootImpl.java:2171)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1931)
// 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1107)
// 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6013)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:606)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



