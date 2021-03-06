

# TODO

_feel free to be **ahead** of schedule_

DEADLINE: Sept. 10th
[ ] Script
[ ] Design most panels on paper
[ ] Sufficiently-featured editor
    [ ] Character scaling
    [-] Mouth + eyebrows?
    [ ] Rotate images
    [X] ~~Export~~
    [X] ~~Artboards~~
    [X] ~~Linking Entities~~
[ ] 

DEADLINE: Sept. 15th
[ ] Fully commented
[ ] Mobile support
[ ] Test on older browsers
[ ] MVP, design at least a few pages in editor, export, make interactive, work on mobile, font-scaling?

DEADLINE: Sept. 20th
[ ] Website
[ ] All designs done + interactive
[ ] Branch editor, no more editing until release

DEADLINE: Sept. 30th
[ ] All playtests done
[ ] Release

## General

[X] ~~Tidy up TODO list~~
[X] ~~ADD COMMENTS TO EVERYTHING~~
[ ] ADD MORE COMMENTS
[ ] Support older browsers
[2] Design actual pages on paper
[X] ~~Export HTML~~
[X] ~~Export CSS~~
[X] ~~Export JS~~
[ ] Only variable names & classes for entities marked as interactive
[ ] Set options and handle positions in JS export
[X] ~~Export as zip with images~~
[X] ~~Save to filesystem~~
[ ] Load from filesystem
[X] ~~Offset handles~~
[ ] Embed scripts to make interactive
[ ] remove "_" from the start of like every function ever...
[ ] only pay attention to `/*++++*/` instead of applyCallbacks
[X] ~~make save json slightly more compatible with future versions~~
[X] ~~Link panel between artboards for mobile support and such!~~
[X] ~~Saving Symbolic Link Entities~~
[X] ~~Export contents of ArtBoards~~
[?] Modify export for symbolic link entities
[ ] Update handle offset based of entity's transformation matrix?...
[X] ~~Figure out what we're going to do with pages~~
[ ] Figure out how switching between desktop & mobile will work with iFrame?

## Bugs

[ ] Fix handles snapping when not being dragged
    [ ] handles still need to snap, just not when their parents are being dragged
[ ] Fix Entities not toggling back in Panel on undo/redo
[ ] Pull copy/paste out of panel
[X] ~~Fix update scale on ImportEntity~~
[x] ~~Fix handle positioning when moved in and out of container~~
[ ] Save textEntity merge

## Entities
[-] Select multiple entities
[-] Move multiple selected entities
[-] Delete multiple selected entities
[?] Locking entities

[-] Allow entity to be masked by MULTIPLE panels
[-] if masked by multiple panels, highlight panels when entity selected

[-] Allow any entity to subtract from panels
    [X] ~~dialate filter~~
    [-] fix border mod?

## TextEntity
[?] TextEntity Height based off `<p>`?
[X] ~~Text-centering for TextEntity~~
[-] Use table-cell for centering
[X] ~~Some sort of Markdown HTML format for TextEntity (edit: HTML)~~
[-] Figure out textwrapping for circular shaped boxes? or just no circles, or just put rect within circle (probably best option)
[-] Add new shapes / shape modifications for speech bubbles
    [X] ~~no shape!~~
[X] ~~Tail type select box~~
    [ ] Option to convert tail to connector (tail type?)
[ ] Tail curving
[X] ~~Join two speech bubbles~~
[X] ~~separate TextEntity into seperate classes~~


## Character
[!] Scaling Character
[ ] Shirt Logo for Character
[?] Mouth for Character
[X] ~~Hair for Character~~
[X] ~~Seperate hair into class~~
[-] Hats for Character
[X] ~~Seperate character into multiple classes~~
[X] ~~Change skin color~~
[X] ~~Change body color~~
[X] ~~Change hair color~~
[ ] hair shading?
[ ] Glasses?

## ImportEntity
[X] ~~Load image from directory~~
[X] ~~Scaling (locked to aspect ratio)~~
[ ] Rotation

## Panel
[ ] control light direction

## Artboards
[X] ~~Create Artboard Entity~~
[X] ~~Create container subEntity~~
[X] ~~Place Entities in Artboard automatically?~~
[X] ~~Link copy (for secondary artboards?)~~
[X] ~~Create ONLY Desktop & Mobile artboards~~
[X] ~~ONLY export contents of artboards?~~
[X] ~~parent entities' positions inside artboards and panels to the position of the artboard / panel? that will fix some problems!~~
[X] ~~fix problems made by parenting entities' positions inside artboards...~~

## Pages
[ ] create multiple pages, switch between

