# Shared Notes Project

These are the commands I had done:  

   1  **mkdir notes-project**  
   2  **cd notes-project/**  
   3  **git init**  
   4  **mkdir notes**  
   5  ls  
   6  git branch note-alice  
   7  git branch note-bob  
   8  ls  
   9  git init  
   10  ls  
   11  echo "# Shared Notes Project" > README.md  
   12  git add .  
   13  git commit -m "Initial commit"  
   14  ls  
   15  **git branch note-alice**  
   16  **git branch note-bob**  
   17  ls  
   18  git branch  
   19  **git checkout note-alice**   
   20  **touch note1.md**  
   21  echo "Alice Note" > note1.md   
   22  ls  
   23  mv note1.md notes  
   24  ls  
   25  ls notes  
   26  cd notes/note1.md  
   27  cd notes/  
   29  cat note1.md   
   30  cd ..  
   31  git branch  
   32  cd notes-project/  
   34  git branch  
   35  git add .  
   36  **git commit -m "add note1 file"**  
   37  **git checkout note-bob **  
   38  ls  
   39  git checkout note-alice   
   40  ls  
   41  git checkout master   
   42  ls  
   43  git branch  
   44  git checkout note-b  
   45  **git checkout note-bob **  
   46  **touch note2.md**  
   47  echo "Bob note" > note2.md   
   48  mv note2.md > notes  
   49  cat note2.md   
   50  ls  
   51  mv note2.md notes  
   52  ls  
   53 ls notes   
   54  ls  
   55  cd notes  
   56  mv notes note2.md   
   57 ls  
   60  mkdir notes  
   61  mv note2.md notes  
   62  ls  
   63  ls notes/  
   64  cat note2.md  
   65  cd ..  
   66  ls  
   67  cd notes-project/  
   68  ls  
   69  git branch   
   70 git add .  
   71  git commit -m "add note2 file"  
   72  git branch   
   73  **echo "Shared file" > notes/shared.md**  
   74  ls  
   75  ls notes/  
   76  cat shared.md  
   77  cat notes/shared.md   
   78  git add .  
   79  git commit -m "Bob edits the shared file"  
   80  git branch   
   81  cd switch note-alice  
   82  git checkout note-alice   
   83  **echo "Shared file" > notes/shared.md**  
   84  **git add .**  
   85  **git commit -m "Alice edits the shared file"**  
   86  git checkout master   
   87  g**it merge note-alice **  
   88  git merge note-bob   
   89  git branch   
   90  git checkout note-alice   
   91  ls  
   92  ls notes/  
   93  cat notes/shared.md   
   94  cat notes/note1.md   
   95  git checkout note-bob   
   96  ls  
   97  ls notes/  
   98  cat notes/note2.md   
   99  cat notes/shared.md 
  100  **echo "Bob edits the shared note" > notes/shared.md **  
  101  cat notes/shared.md   
  102  git add .  
  103  git commit -m "edit the shared notes in note-bob   file"
  104  git checkout master   
  105  **git merge note-bob**  
  106  git status  
  107  git remote add origin https://github.com/asmabch/  notes-project.git  
  108  git push -u origin main  
  109  git branch  
  110  git push -u origin master  
  111  ls ~/.ssh  
  112  cat ~/.ssh/id_ed25519.pub   
  113  git remote -v  
  114  git remote set -url origin git@github.com:asmabch/notes-project.git  
  115  **git remote set-url origin git@github.com:asmabch/notes-project.git**  
  116  ssh -T git@github.com  
  117  git push -u origin master  
  118  ssh -T git@github.com  
  119  ssh-keygen -R github.com  
  120  mkdir -p ~/.ssh  
  121  chmod 700 ~/.ssh  
  122  ssh -T git@github.com  
  123  **git push -u origin master**  
  124  **git push origin note-alice**  
  125  **git push origin note-bob**  
  126  **nano .git/hooks/pre-commit**  
  127  **chmod +x .git/hooks/pre-commit**  
  128  echo "" > notes/note2.md  
  129  git add notes/note2.md  
  130  git commit -m "Test empty title"  
  131  echo "Note 2" > notes/note2.md  
  132  git add notes/note2.md  
  133  git commit -m "Add note to note2 file"  
  134  git push origin master   
  135  history  
  136  history > my_terminal_history.txt  
  137  cd ..  
  138  history | grep "$(date +%F)"  
  139  history | grep "$(2025-12-19 +%F)"  
  140  history | grep "$(date +%F)" > todays_history.txt  
  141  export HISTTIMEFORMAT="2025-12-19 "  
  142  history  
  143  history > my_terminal_history.txt  
  144  export HISTTIMEFORMAT="$F"  
  145  history > my_terminal_history.txt  
