let-over-lambda
===============

Doug Hoyte's "Production" version of macros from Let Over Lambda, ready for ASDF and Quicklisp.

Read more about the book and code at: http://letoverlambda.com

Includes compiler optimizations by Jorge Gajon <gajon@gajon.org>.

Tested with SBCL 1.1.7+ on Linux and OS X.

Usage
-----

    * (ql:quickload "let-over-lambda")
    
    * (lol:flatten '((A . B) (C . D) (E . (F G H (I . J) . K))))
    
    (A B C D E F G H I J K)

