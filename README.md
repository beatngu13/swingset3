# Evaluation of Swing-compatible Capture and Replay Tools #

This SwingSet3-based project, forked from https://github.com/sjas/swingset3 (originally taken from the SVN repository at https://java.net/projects/swingset3), has been used to evaluate various Swing-compatible capture and replay tools as part of a research project at my alma mater. The results of this study (German report) can be [requested](mailto:daniel.kraus@mailbox.org) on demand.

Though I changed the sources in order to run several tests, commits until `999b897` (Nov 10, 2015) do not include these changes. Hence, this revision can be used to have an *Eclipse-ready Git clone of the original SwingSet3*. Simply checkout the repository, switch to the branch `feature/eclipse`, add the JARs from `lib` and `javaws.jar` (usually in `${JAVA_HOME}/jre/lib`) to your class path and run the main method within `com.sun.swingset3.SwingSet3`.
