# company-c-preprocessor
add backend for c/c++ prerpocessor.

** Installation

*** from git
 git clone https://github.com/fredericfrances/company-c-preprocessor.git 
 in your .emacs
 #+BEGIN_SRC emacs-lisp
 (add-to-list 'load-path "<path to company-c-preprocessor clone directory>")
 #+END_SRC  
Add this in emacs load path.


melpa comming soon.

** Setup
#+BEGIN_SRC emacs-lisp
 (require 'company-c-preprocessor)
 (add-to-list 'company-backends 'company-c-preprocessor)
#+END_SRC  
