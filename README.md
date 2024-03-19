# toba
Toba is an extensible personal information retrieval desktop application. It comes with the ability to store and search notes, tasks, references to web pages, and business opportunities, but can be extended to store and retrieve almost anything.

SCR# 962

https://sourceforge.net/projects/toba

CVS is an old system for managing code. In order to access a CVS repository, you must install a CVS client.
The CVS data can be accessed as follows. You can run a per-module CVS checkout via pserver protocol:

cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/toba co -P BusinessOppPlugin
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/toba co -P ExtraDistDocs
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/toba co -P JASEPlugin
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/toba co -P JepPlugin
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/toba co -P JythonPlugin
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/toba co -P Toba
cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/toba co -P WNotePlugin

You can view a list of files or copy all the CVS repository data via rsync (the 1st command lists the files, the 2nd copies):

rsync -a a.cvs.sourceforge.net::cvsroot/toba/
rsync -ai a.cvs.sourceforge.net::cvsroot/toba/ /my/local/dest/dir/
