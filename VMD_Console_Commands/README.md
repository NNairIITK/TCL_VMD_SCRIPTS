
TCL VMD SCRIPT TO ANALYSE TRAJECTORY and Can be UTILIZED as CUSTAMIZED COMMANDS in VMD

 VERSION  : analysis_script_V 1.0

 Authour  :  ANJI BABU KAPAKAYLA
             IIT KANPUR, INDIA.
             ( anjibabu480@gmail.com)

 Step 1    :  SOURCE analysis.tcl in VMD Tk  console
 Step 2    :  Command_name {Arguments}


 After Sourcing analysis.tcl script in VMD console, type following
    my_commands show     : List out all available commands from this script.
    --help command_name  : Shows the details of command ,with examples.

================================================================================================
TIP OF THE DAY  :

     Keep this analysis.tcl script in a adirectory called vmd_tcl_scripts/
     Mention its path in vmd startup file ~/.vmdrc

        eg.   source /home/anjibabu/vmd_tcl_scripts/analysis.tcl

      That's it, here after when ever you open VMD automatically analysis.tcl will be excecuted.
      So, U can start using these commands as default commands.
=================================================================================================
