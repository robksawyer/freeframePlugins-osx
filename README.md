# sfFreeFrame Plugins (OSX Version)
> sfFreeFrame is a collection of open source visual plugins for [FreeFrame 1.5](http://sourceforge.net/projects/freeframe/?source=typ_redirect) compatible hosts. This means they can be used for live visual performance using programs like Resolume Avenue, VDMX, MaxMSP/Jitter and more. 

## Dependencies 
- Open Frameworks <https://github.com/robksawyer/openFrameworks>
- Apple Xcode <https://developer.apple.com/xcode/>

### Before starting. Check the required includes and addons.
> Verify that you have the following addons and libraries installed in your openframeworks project folder.

#### OpenFrameworks Libraries
- [libs/openFrameworks](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks)
- [libs/openFrameworks/graphics](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks/graphics)
- [libs/openFrameworks/app](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks/app)
- [libs/openFrameworks/sound](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks/sound)
- [libs/openFrameworks/utils](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks/utils)
- [libs/openFrameworks/communication](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks/communication)
- [libs/openFrameworks/video](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks/video)
- [libs/openFrameworks/events](https://github.com/robksawyer/openFrameworks/tree/master/libs/openFrameworks/events)
- [libs/glut/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/glut)
- [libs/rtAudio/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/rtAudio)
- [libs/quicktime/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/quicktime)
- [libs/freetype/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/freetype)
- [libs/freetype/include/freetype2](https://github.com/openframeworks/openFrameworks/tree/master/libs/freetype/include/freetype2/freetype)
- [libs/FreeImage/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/FreeImage)
- [libs/fmodex/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/fmodex)
- [libs/videoInput/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/videoInput)
- [libs/glu/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/glu)
- [libs/poco/include](https://github.com/robksawyer/openFrameworks/tree/master/libs/poco)

#### OpenFrameworks Addons
> Not familiar with addons? See <http://www.ofxaddons.com/pages/howto>

- [addons](https://github.com/robksawyer/openFrameworks/tree/osx-ffgl/addons)
- [addons/PennerEasing](https://github.com/robksawyer/ofxAddons/tree/master/PennerEasing) - Took a bit of searching to find this.
- [addons/ofxNoise/src](https://github.com/robksawyer/ofxRuicodeAddons/tree/master/ofxNoise/src) - This was ported from <http://code.google.com/p/ruicode>.
- [addons/ofxVectorMath/src](https://github.com/robksawyer/openFrameworks/tree/0071/addons/ofxVectorMath/src) - DEPRECATED at Tag 0072: Included only for backwards-compatibility. See post <http://forum.openframeworks.cc/t/ofxvectormath/7028>. See [Old Tags](#old-tags) below.
- [addons/ofxFFGLPlugin/src](https://github.com/robksawyer/openFrameworks/tree/osx-ffgl/addons/ofxFFGLPlugin/src) - Be sure to check out the [README.md](https://github.com/robksawyer/ofFFGLPlugin) on this one. There have been modifications made from the original version of ofxFFGLPlugin that is downloaded from <https://code.google.com/p/ofxffglplugin/>.
- [addons/ofxFFGLPlugin/libs/FFGL](https://github.com/robksawyer/openFrameworks/tree/osx-ffgl/addons/ofxFFGLPlugin/libs/FFGL) - Be sure to check out the [README.md](https://github.com/robksawyer/ofFFGLPlugin)

#### Other Libraries

- [sfLibrary/src](https://github.com/robksawyer/freeframePlugins-osx/tree/master/sfLibrary/src) - I put this in the `openframeworks/other/` folder.
- [libs/glee/include](https://github.com/openframeworks/openFrameworks/tree/0062/libs/glee) - DEPRECATED at Tag 0062: Included only for backwards-compatibility until I can figure out how to remove it. See [Old Tags](#old-tags) below.


## Install
1. git clone the project into your open frameworks `app` project folder at the root: `openframeworks_v0.8.4/apps/freeframePlugins-osx`
2. Run one of the `.xcodeproj` files. (COMING SOON)

## Old Tags

In order to use this project, you'll need to install some libraries that are no longer included with OpenFrameworks. To do so you should checkout the mentioned tag via the specific repo mentioned ([openframeworks](https://github.com/robksawyer/openFrameworks)) and copy the folder to your working openframeworks build or somewhere else until you switch back to your working copy. See <http://stackoverflow.com/questions/791959/download-a-specific-tag-with-git>

## FAQs

1. How do I fix the `tr1/memory file not found` error?
  > See the post <https://github.com/openframeworks/openFrameworks/issues/2686>.


## Resources
- [Basics of OpenFrameworks](http://openframeworks.cc/tutorials/graphics/opengl.html)
- [OpenFrameworks Documentation](http://openframeworks.cc/documentation/)

sfFreeFrame plugins are developed by Marc Wren / <http://soul-fresh.com>. For more information about FreeFrame please visit <http://freeframe.sourceforge.net/>.
