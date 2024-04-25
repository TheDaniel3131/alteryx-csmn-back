---
{"dg-publish":true,"permalink":"/alteryx-prep-notes/notes-md/","noteIcon":"","created":"2024-04-25T15:20:52.467+08:00","updated":"2024-04-25T23:01:23.134+08:00"}
---


**I. Use Designer search and resources (20% of the exam)**

- The search bar in Alteryx Designer is a great first stop for help. [It aggregates results from the tool palette, help documentation, and the Alteryx Community](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[1](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[2](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface/search.html).
- [You can search for a topic, concept, or method and quickly find what you need](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[1](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452).
- [Alteryx Designer provides various resources such as one tool examples, community discussions, and help pages](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[1](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452).

**II. Navigate the user interface (20% of the exam)**

- [Alteryx Designer’s user interface consists of several components that you can move, resize, reorganize, or close](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface.html)[3](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface.html).
- [The Workflow canvas is where you build a workflow](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface.html)[3](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface.html).
- [The Tool Palette consists of tools organized into tool categories](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface.html)[3](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface.html).
- [You can customize the layout of the user interface](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface/customize-the-user-interface.html)[4](https://help.alteryx.com/current/en/designer/get-started/designer-user-interface/customize-the-user-interface.html).

**III. Identify Alteryx native file formats (40% of the exam)**

- [Alteryx has several native file extensions such as .yxmd (Workflow), .yxdb (Alteryx Database), .yxmc (Macro), .yxwz (Analytic App), .yxzp (Packaged Workflow), and .yxi (Packaged Tool)](https://help.alteryx.com/current/en/designer/file-types-support/alteryx-file-types.html)[5](https://help.alteryx.com/current/en/designer/file-types-support/alteryx-file-types.html).
- [The .yxdb format is the most efficient file type for reading and writing in Alteryx because it has no size limit, is compressed for maximum speed, and includes additional metadata](https://downloads.alteryx.com/betawh_xnext/Reference/yxdb.htm)[6](https://downloads.alteryx.com/betawh_xnext/Reference/yxdb.htm).

List of filetypes/file formats: https://help.alteryx.com/current/en/designer/file-types-support/alteryx-file-types.html#idm45439280187328

**IV. Share and export workflows (20% of the exam)**

- [You can save the workflows you build in Alteryx Designer so that you can reuse them or share them with other users](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[7](https://help.alteryx.com/current/en/designer/workflows/workflow-management.html).
- [If you want to save and share a workflow along with its dependencies, such as files and connections, you can export them together as a .yxzp file](https://help.alteryx.com/current/en/designer/workflows/workflow-management.html)[7](https://help.alteryx.com/current/en/designer/workflows/workflow-management.html)[8](https://help.alteryx.com/2019.3/ModulePackager.htm).
- [You can also save multiple workflows as a workflow group that you can then open as 1 workflow group file (.yxwg)](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[7](https://help.alteryx.com/current/en/designer/workflows/workflow-management.html).

You need to know what types of files you can work with in alteryx.

![Pasted image 20240425152547.png](/img/user/Pasted%20image%2020240425152547.png)

![Pasted image 20240425152615.png](/img/user/Pasted%20image%2020240425152615.png)

**V. Optimize workflows by reducing run time and using documentation tools (20% of the exam)**

- [You can optimize Alteryx workflows by reducing the amount of data, removing unnecessary tools, using the record limit option, and documenting the workflow](https://www.youtube.com/watch?v=zcSdFwKtnEQ)[9](https://www.youtube.com/watch?v=zcSdFwKtnEQ).
- [Some tools commonly take up a large amount of processing time as a percentage of the total](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[10](https://www.popautomation.com/post/top-10-alteryx-optimize).
- [You can use the Select tool to remove fields you are not using as early as possible in a stream](https://community.alteryx.com/t5/Engine-Works/Helpful-Resources-Inside-Alteryx-Designer/ba-p/1168452)[11](https://help.alteryx.com/2020.2/WorkflowOptimization.htm?tocpath=Workflows%7C_____5).
- [You can use the Sample tool on large record sets to limit the number of records passing through the workflow](https://help.alteryx.com/2020.2/WorkflowOptimization.htm?tocpath=Workflows%7C_____5)[11](https://help.alteryx.com/2020.2/WorkflowOptimization.htm?tocpath=Workflows%7C_____5).