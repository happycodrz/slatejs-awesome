### Slate.js

- https://docs.slatejs.org/

  - [Mini Google Docs Clone in React - Intro](https://www.youtube.com/watch?v=CmuUQymjbRo&list=PLN3n1USn4xllb05dQVmRbVtGP2aM4seVq)

    - [Adding Custom Styles in Slate.js](https://www.youtube.com/watch?v=EIolal0VsoE) ()
    - [Automatically Saving Slate.js Editor](https://www.youtube.com/watch?v=lsmsaQXOzTw)
    - [Slate.js Syncing Operations with an Event Emitter](https://www.youtube.com/watch?v=ThN_1Kgald8)

  - [1. Building a rich text editor in React with SlateJS](https://www.youtube.com/watch?v=wLjx67aNEMI)
  - https://hackernoon.com/how-we-built-a-rich-text-editor-in-react-with-slatejs-ni153z3b
  - https://medium.com/@bansalsushil_34403/customising-slate-js-part-1-adding-material-ui-c98568951258
  - https://medium.com/@bansalsushil_34403/how-to-customise-slate-js-part-2-adding-image-upload-functionality-3320a7260966#6adc
  - https://www.tiny.cloud/blog/real-time-collaborative-editing-slate-js/
  - https://www.christopherbiscardi.com/post/rendering-trees-with-slate-js
  - https://joshtronic.com/2020/04/12/resetting-a-slatejs-editor-to-an-empty-state/

  built with slate: - https://www.prezly.com/news/the-different-ways-to-use-images-in-your-prezly-stories - https://writingstreak.io/ - https://nulis.io/ - https://www.temi.com/good-audio-quality (very cool!)

        The whole point of slate is an immutable representation of a document. Without getting too much in the weeds, a document is an immutable object. Edits to the document are transforms. The obvious benefit is undo/redo is pretty simple. The more subtle benefit is that really complicated document rules become tractable. I built temi.com using this (https://www.temi.com/good-audio-quality). One feature that Slate enables pretty easily is incremental saves. Since the object is immutable, you can pass changes to the server instead of the entire document by just checking element ids. You can get multi-person edits relatively easily as well.

        - https://operational-transformation.github.io/ (WOW!)

  Code: - https://github.com/matrix-org/matrix-react-sdk/pull/1890/files

### Community

- https://stackoverflow.com/questions/tagged/slatejs?sort=active&pageSize=50
