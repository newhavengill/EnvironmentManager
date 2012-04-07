Access Oracle Schema From Command Line:

I want to run queries against the schema via shell.  I want as minimal of an Oracle foot print on my local box as possible.  In order to use SQLPlus I have to install Oracle locally.  Instant Client is a nice
work around.  I can run SQLPlus from the command line without having to install the world.

http://www.oracle.com/technetwork/topics/intel-macsoft-096467.html

Here's a quick InstantClient install --> http://www.digitalsanctum.com/2007/07/26/installing-oracle-instant-client-on-mac-os-x/

Yet another quick install link --> http://www.pixellatedvisions.com/2009/03/25/rails-on-oracle-part-1-installing-the-oracle-instant-client-on-mac-os-x

$ dblogin -e local foo