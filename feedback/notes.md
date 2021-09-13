# Feedback

_Right click on the file and click Open Preview or `ctrl/cmd + shift + v` to open preview_

## Goals

1.  Working portfolio:

    - For a working portfolio, I think you are close to reaching this.
    - With the majority of the layouts sorted, you just need to add in the project page and tweak some of the sizes.

2.  Practice using Git / Github Flow:

    - Yes, you have 100% achieved this. You will have to keep it up, carry on branching and committing.
    - Your commit messages as well are consistent and informative so keep it up. The more descriptive the better

3.  Application of morning topics
    - Yes, I think you have achieved this goal, you are using pretty all of the topics we have covered.
    - The thing you may want to work on is breaking down your scss files

---

## Specification

1. README - done

2. BRANCHING - done

   - Try a focus on what you are doing once you are done add commit etc then move onto the next part.

3. SCSS - done / to work on

   - Keep on exploring SCSS, look at mixins and other features the pre processor will give you.
   - Try breaking your scss files down even more. e.g. Components is a folder with a scss file for each component. - I will go into this in the to work on

4. Mobile First - done

5. 25 commits - done

6. BEM - done

---

## Overall

As I said during the demo I think you have relished the chance to apply what we covered in the morning into your project. I think you should try out time-boxing your problems as I think you mentioned you were hesitant to ask for help. I am going to give you some constructive feedback to take on to this project and to take forward to your next projects.

---

## To work on
A couple of little notes:

- Update your script in your package.json from `"watch:scss": "sass scss/main.scss scss/main.css"` to `"watch:scss": "sass scss/main.scss main.css"` this is so your css file is on the same level as the index.html. Normally the scss folder would only be scss no css files.

- Normally when we design mobile first we don't add in a media query for mobile as those styles are applied. You only add in media queries when the size goes up. 

Other then that I think you just need to break down your scss files down into folders with lots of little files rather then large files and also complete the project section.

With SCSS:

- Try and keep the `_layout` styles separate from the `_component` files.
- In the next project have a go at treating your `_components.scss` as a folder with your components in.
- Each component will be its own .scss file with its media queries in there. This will make it easier to navigate once you are use to it.
- In main you bring them all together in there.

Project section:

- You will need to complete this, let me know if you need a hand planning it out / breaking it down.
