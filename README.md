JAKTouch
========

Display Touch Events in all interfaces

Just copy JAKTouch.h and JAKTouch.m in your project.

Add:
1)QuartzCore.framework to your project
2)  [JAKTouch install];


Process:

In your Appdelegate, just add

#import "JAKTouch.h"


//And in:

- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions
{

//After 

[self.window makeKeyAndVisible];

//Call

    [JAKTouch install];


}
