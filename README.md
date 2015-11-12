# Evaluation of Swing-compatible Capture and Replay Tools #

SwingSet3, forked from https://github.com/sjas/swingset3 (originally taken from the SVN repository at https://java.net/projects/swingset3), will be used to evaluate various Swing-compatible capture and replay tools. Sources will change over time in order to simulate the software development process and increase the difficulty.

Commits until `999b897` (Nov 10, 2015) do not include these changes. Hence, this revision can be used to have a Eclipse-ready SVN clone of the original SwingSet3. Simply checkout the repository, switch to the branch `feature/eclipse`, add the JARs from `lib` and `javaws.jar` (usually in `${JAVA_HOME}/jre/lib`) to your class path and run `com.sun.swingset3.SwingSet3`.
