#RecRoom Interactions and Prototypes
This page contains notes about the RecRoom user experience and about the IA prototypes.

- RecRoom User Experience
- [RecRoom IA prototypes](#proto)


##<a name="ux"></a>RecRoom User Experience
RecRoom is a stepping stone to the App Center. It's where you go first if you are just starting out with Open Web Apps.

**The recommended user experience for RecRoom is that it lives on its own site.**  And is accessible from several points within the App Center and MDN. 

[See reasons below](#reasons)

For the MVP, we can fit it into the App Center temporarily if we want to do that. This is a less-than-ideal solution though that will dilute the usefulness of RecRoom. 


##<a name="proto"></a>RecRoom IA Prototypes

*NOTE: Not all links are hooked up in the prototypes. Red links are changes I'm recommending to pages outside of RecRoom. Some pages are still in-progress.*

**[Sitemap][1]**
- Sitemap is based on intial TOC for RecRoom content. [See intial TOC][2].
- Design goal: Create smaller chunks that user can navigate through using next/previous.

**[MDN landing page][3] - start here**
- Includes callout for RecRoom

**App Center landing page**
- Replace Quickstart with Get Started driving to RecRoom landing page
- Modify copy and links under Build block

**Tools and Frameworks page**
- Includes callout for RecRoom

**RecRoom landing page**
- Includes recommended navigation for RecRoom using modified style from MDN

**Get Started page**
- This is an example of a **Text page type.** 
- Includes a right-side quicklinks area. These are links to content on this page and to pages external to RecRoom.
- Includes link at bottom of content sending user to the next section of the site -- First App Tutorial.

**First App Tutorial pages**
- These are examples of **Tutorial page types.** Tutorial page types contain buttons at the bottom of the contentso user can navigate navigate in a linear way through the steps. The leftnav shows these pages as well, for users who want to skip around.
- At the end of this specific tutorial, user would be directed to the next section of the site -- Best Practices. Other tutorials may or may not have a similar CTA - we'll see as the content is developed.
- Includes some recommendations for language, formatting, tip style, and contextual help.
 
**General RecRoom**
- Best Practices and Resources contain sub-landing pages accessible by hovering over their names in the main nav bar. Each of those pages will branch out into sub-pages and will use the same leftnav as for the First App Tutorial.

**Other Page and Content Types**
- Process Page Type - may not need this; might be same as Tutorial. TBD depending on content developed.
- Use Cases content block - On Best Practices pages, will use a special visual style to set up the context for when user might want to use the best practice in question. 
- More Page Types or Content Types may be needed as content is developed.
 
 
##<a name="reasons"></a>Why RecRoom Needs Its Own Site

RecRoom content differs from other App Center content in that it has an opinion about how users should progress through it. This means that its navigation methods must support linear progression (though not mandate this). 

Navigation methods within the App Center support wandering rather than progression. We could re-architect the App Center so it supports linear progression and browsing (I have tons of ideas). But this seems outside our scope for now...let me know if I'm wrong about that.

RecRoom content is best presented as many short-ish pages (rather than fewer longer pages). This means that we'll create a hierarchical architecture where there are landing pages, sub-landing pages, and leafs below those ([see Sitemap][1]). Again the App Center architecture doesn't support this at this time.

The existing App Center only has 2 levels of navigation (though the content goes much deeper than this). Adding RecRoom will add 2 additional levels of navigation. Combined with the overarching MDN navigation, there are too many levels when RecRoom is included.

RecRoom content is for a different audience than the App Center. The App Center is designed as a reference tool for people who generally know what they're doing. RecRoom is for people who don't want all the backstory; they just want some guidance and recommendations that let them start coding right away.


[1]: http://585RIV.axshare.com "RecRoom Sitemap"
[2]: https://github.com/mozilla/recroom-docs/blob/master/README.md "RecRoom TOC"
[3]: http://HI0P02.axshare.com "RecRoom prototypes"


