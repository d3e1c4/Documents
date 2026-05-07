
**git init** : Initializes a brand new Git repository in your current folder. It creates a hidden `.git` folder to track changes.
**git add .** : Moves all new or modified files to the **Staging Area**. Think of this as "preparing the files" before they are officially saved.
git commit -m "first commit" : Takes a snapshot of your staged files and saves them permanently in the local database. The `-m` stands for "message," which describes what you changed.
git branch -M main : Renames the default branch to `main`. (Older versions of Git used `master` as the default).
git remote add origin [URL] : Connects your local repository to a remote repository on GitHub. `origin` is just a nickname for that URL.
git push -u origin main : Uploads your local commits to the GitHub repository. The `-u` flag sets the "upstream," meaning in the future, you can just type `git push` or `git pull` without specifying the branch.

git config user.name "Your Name"
git config user.email "your_student_email@example.com"

**`git status`**: It shows which files are modified, which are staged, and what branch you are currently on.`

**`git pull`** සහ **`git fetch`** යන කමාන්ඩ් දෙකම භාවිතා කරන්නේ GitHub (Remote Repository) එකේ ඇති අලුත් වෙනස්කම් ඔබේ පරිගණකයට (Local Repository) ලබා ගැනීමටයි. නමුත් ඒවා ක්‍රියාත්මක වන ආකාරයේ විශාල වෙනසක් ඇත.

ප්‍රධාන වෙනස මෙන්න:

### 1. `git fetch` (ආරක්ෂිත ක්‍රමය)

- **සිදු වන දේ:** GitHub එකේ ඇති අලුත් **`commits`**, **`branches`** සහ වෙනස්කම් ඔබේ පරිගණකයට ඩවුන්ලෝඩ් (Download) කරනවා පමණයි.
    
- **ඔබේ කේතයට වන දේ:** මෙය ඔබේ දැනට වැඩ කරන ෆයිල් වලට (Working Directory) කිසිදු වෙනසක් කරන්නේ නැහැ. අලුත් කේත ඔබේ කේත සමඟ එකතු (Merge) නොවන නිසා මෙය ඉතා ආරක්ෂිතයි.
    
- **භාවිතා කරන්නේ ඇයි?:** අනිත් අය කරලා තියෙන අලුත් වෙනස්කම් මොනවාදැයි බලා ගැනීමට සහ ඒවා එකතු කිරීමට පෙර පරීක්ෂා කිරීමට.
    

### 2. `git pull` (වේගවත් ක්‍රමය)

- **සිදු වන දේ:** මෙය කමාන්ඩ් දෙකක එකතුවකි (**`git pull` = `git fetch` + `git merge`**). මෙය මගින් අලුත් වෙනස්කම් ඩවුන්ලෝඩ් කරගෙන, ඒ වෙලාවෙම ඒවා ඔබේ ෆයිල් වලට එකතු (Merge) කරනවා.
    
- **ඔබේ කේතයට වන දේ:** ඔබේ දැනට වැඩ කරන ෆයිල් (Working Directory) අලුත් වෙනස්කම් සමඟ යාවත්කාලීන (Update) වේ.
    
- **අවදානම:** මේ වෙලාවෙම කේත එකතු වන නිසා, ඔබේ කේත සහ අලුත් කේත අතර ගැටෙන තැන් තිබුණොත් **`Merge Conflicts`** (ගැටළු) ඇති වෙන්න පුළුවන්.
    

**කෙටියෙන් මතක තබා ගැනීමට:**

- **`fetch`** කියන්නේ තැපැල් කන්තෝරුවට ලියුම් ඇවිත් තියෙනවාද කියලා ගිහින් බලනවා වගේ වැඩක් (ඔබට අවශ්‍ය නම් විතරක් ගෙනල්ලා කියවන්න පුළුවන්).
    
- **`pull`** කියන්නේ තැපැල්කාරයා ලියුම් ගෙනත් ඔබේ අතටම දෙනවා වගේ වැඩක් (එය කෙලින්ම ඔබේ වැඩවලට බලපානවා).