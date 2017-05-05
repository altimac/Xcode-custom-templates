I learned Cocoa a little less than 2 decades ago when we had no storyboard, no autolayout, no NSViewController (and no installed NSWindowController!). I miss the simplicity of the default Cocoa Application project template where just adding NSObject subclasses to the MainMenu.xib was enough to instantiate them at runtime. This was convenient and really easy to learn.

Today, I'm also a Cocoa trainer and I can't explain Storyboards, Autolayout, NSViewController/UIViewController on day one to the students, when then hardly know what ObjC is and what alloc+init does. To reduce the learning curve and hook them as soon as possible to Cocoa, i've customized some Xcode templates for a kickstart dive in Cocoa.



# Xcode-custom-templates
Various Xcode custom templates, targeting minimalistic content (No Storyboard, No Autolayout...) used for my trainings.

# Mac application template:
# Install in `~/Library/Developer/Xcode/Templates/Project Templates/Mac/Application/`
- No default Storyboard (use MainMenu.xib instead)
- No Autolayout set by default
- A mininimal AppDelegate implementation (with a property for the main window)
- ObjC and Swift compatible
- Xcode 8.3 compatible

Use without any restriction.
