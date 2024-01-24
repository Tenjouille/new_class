# new_class
Script to quickly create new classes

With this script, you will be able to create pretty simply the base of a new class respecting the canonic form for your c++ project.
Include a ${Class_name}.hpp, a ${Class_name}.cpp, a Makefile and an empty main.

# How to use new_class
Really simple, execute it with the name you wanna give to your new class as first argument, and the path to repertory you wanna create those files.
(Exemple : ./new_class.sh SimpleClass .)





# WARNING
This script has been made in the context of my formation at 42, so you can also find 42 header at the start of every file except Makefile. 
Since it is using you current env var $USER to create it, the format can be undefined if it does not correspond to the 42 login format (max 8 characters)

Credits : Juduval for the features
          Tgibier for the Makefile template
