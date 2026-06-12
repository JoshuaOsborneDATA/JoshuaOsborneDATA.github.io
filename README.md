<ins>Portfolio</ins>  
My portfolio can be found at https://joshuaosbornedata.github.io/  
**What's in there?** All my projects, current publications, and work experience, and in-progess projects



<ins>Notes</ins>  
**What's in there?** So far, not much, but I intend to build upon it little by little every day. The idea is to have a resource where you can  
find anything you need related to statistcs (descriptive statistics, A/B testing, probability theory, machine learning, etc.).  

**Why?** For one, it acts as personal notes for myself. Two, sometimes I want to know where an equation came from and I want to know what it's  
related to. So my goal is to have a set of notes that does just that (we'll see how it goes and if I stay true to that idea!). I'm hoping that  
it helps others along the way as well!  

**Where the notes are located:** At https://github.com/JoshuaOsborneDATA/Notes_html
  
**Contributions:** If you want to add on to the notes, see something wrong, or see something missing then feel free to contribute or correct me!  
If you also want to take the notes and make it into your own, feel free. Currently I use obsidian and use wikilinks so the build script will  
take care of that for you if you are using obsidian as well. For contributions, this is what I have currently, but if you have a better idea please let me know!  
  
1. Write the note in your own vault (notes_folder/) inside the relevant subject folder. Use _build/note-template.md as your starting structure. Notes can have additional
  sections beyond the template.
2. Create the sidecar yaml in the same folder, named to match your .md file. in other words your .md and .yaml must be next to each other:
My Note.md  →  My Note.yaml
2. Use _build/note-template.yaml as a guide. At minimum, set title and description. Add author with your name. Set prev/next if your note fits into an existing sequence,
otherwise leave them out.
3. Place any figures (PNGs, GIFs) into ./notes_html/images/.
4. Run the build from ./notes_html/:  
  
    To build everything in the vault with the same structure as the notes:
    python3 _build/build.py /workspace/notes/ /workspace/notes_html/
