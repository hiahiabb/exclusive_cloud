# 权限管理

权限管理是在权限组件进行扩展开发的，提供用户管理、角色管理、授权管理等功能。主要流程是，建立用户和角色后，在【用户管理】或【角色分配用户】中分配角色，在【角色管理】或【功能授权】中把功能分配给角色。

在应用平台里权限管理主要提供用户管理、角色管理、角色分配用户、功能授权、按钮授权、小部件授权和数据权限。

## 用户管理

用户管理：用于创建系统内用户，属于系统类和管理类节点。所以只有管理员才可以看到并录入此功能。单击【用户管理】，进入用户管理主界面，如下图所示。界面上方提供功能框与搜索框，支持用户新增与搜索操作。下方按行显示具体用户的具体信息，鼠标放置于某行用户信息上，右侧显示操作按钮。

![](/articles/appspecial/5-/images/image51.png)


 
**新增**

单击〖新增〗按钮创建新用户，弹出下图所示窗口，用户编码、用户名称、手机号、邮箱为必填信息，用户密码为系统默认预置密码。

![](/articles/appspecial/5-/images/image52.png)

**高级搜索**

上方功能菜单栏最右侧提供高级搜索框，可按选项进行搜索，搜索结果为匹配用户列表。

**操作**

鼠标放置于某行用户信息上，右侧显示操作按钮。可以重置密码、编辑用户信息、删除用户信息和启用或停用用户。

**分配角色**

选定用户，单击右侧分配角色的图标按钮，如下图所示：

![](/articles/appspecial/5-/images/image53.png)


 
单击〖选择角色〗按钮可以选择角色，或者取消选择分配的角色：

![](/articles/appspecial/5-/images/image54.png)
 
可以删除或批量删除角色。

## 角色管理

角色是相同岗位所拥有的一组权限的统称，在系统中体现为一些相关的职责，以及数据权限的范围。用户通过扮演不同的角色来完成权限的控制。新增或者编辑系统内角色，并对角色进行相应的管理。单击【角色管理】，进入角色管理主界面，如下图所示。

![](/articles/appspecial/5-/images/image55.png)


 
支持角色与角色相关联的用户显示、管理。角色管理可以进行角色的新增、修改、删除。

**新增角色**

单击〖新增〗按钮，角色编码、角色名称为必填，点击〖保存〗完成增添新角色。

![](/articles/appspecial/5-/images/image56.png)
 
角色编码、角色名称【非空且唯一】。

角色类型：可选项为管理员或者业务员。如果角色为管理类角色，则选择“管理员”。如果角色为业务类角色，则选择“业务员”。

**分配功能**

可以分配在功能管理里创建的小应用，只有给角色分配了对应的功能，此角色关联的用户才可以看到。选定已有角色，单击右边的分配功能按钮，选择功能，点击〖保存〗。

![](/articles/appspecial/5-/images/image57.png)

 
**编辑角色**

选定已有角色，单击右边的编辑按钮，可以对角色信息进行修改。

**删除角色**

选定已有角色，单击右边的删除按钮，删除该角色。

**高级搜索**

可以按选项进行匹配搜索。

## 角色分配用户

此应用的功能是将角色分配给用户。

单击【角色分配用户】，进入角色管理主界面，左侧区域：角色信息；右侧区域：选择的角色，已经分配的用户列表。

![](/articles/appspecial/5-/images/image58.png)
 
**分配用户**

选择特定角色，点击右边的〖分配用户〗按钮，为角色分配关联用户。点击后展示出未被分配的用户，可以选择，并点击〖确定〗。

![](/articles/appspecial/5-/images/image59.png)
 
点击〖确定〗后，选中的数据就会添加到已分配用户区域。

**取消分配用户**

选择特定已分配用户，点击右侧〖取消分配〗按钮，或者选择多个用户，点击〖批量取消分配〗按钮，则选中的数据从“已分配用户”区域删除。如下图所示：

![](/articles/appspecial/5-/images/image60.png)
 
## 功能授权

小应用授权：功能是为业务角色做小应用的功能授权。选择对应的角色，选择“授权”功能，可以将需要的小应用分配给对应的角色。同角色节点上的“分配小应用”功能类似。

左侧区域：展示角色数据。

右侧区域：为选中角色的“已经授权”的小应用列表。

单击【功能授权】，进入功能授权主页面，如下图所示：

![](/articles/appspecial/5-/images/image61.png)
 
**功能授权**

在左侧区域，选择特定角色，点击右侧〖功能授权〗按钮，出现下图界面，图中展示了按照分组展示的所有小应用，在需要授权的小应用下方打勾，点击保存即可完成授权。

取消授权：在小应用下方取消打勾，则可取消授权

![](/articles/appspecial/5-/images/image62.png)


 
最后点击〖保存〗完成授权。

## 按钮授权

针对在“按钮管理”中注册的按钮做授权操作。

左侧区域：展示角色数据。

右侧区域：如果前面已勾选，则说明为选中角色的“已经授权”的按钮列表，否则暂未授权。

如下图中并未给当前角色做按钮授权。

![](/articles/appspecial/5-/images/image63.png)
 
分配过程：

如果需要给当前业务员分配按钮，则需要给“删除”按钮分配权限，并点击〖分配〗，如下图所示，已分配成功。

![](/articles/appspecial/5-/images/image64.png)
 
取消分配过程：

选中对应按钮，去掉对应按钮前面的勾选，再点击分配，则取消分配成功。

## 小部件授权

针对在门户设置里的“小部件管理”中的小部件做授权。单击【小部件授权】，进入小部件授权主页面，如下图所示。界面分为左右两部分，左侧区域显示角色数据，右侧区域显示选中角色的“已经授权”的小部件列表。

![](/articles/appspecial/5-/images/image65.png)

 
➢ 授权功能

点击某个角色右侧的〖授权〗按钮，在需要授权的小部件下方勾选，则授权；

取消勾选，则表示取消授权。

完成后点击〖保存〗，则授权成功。

![](/articles/appspecial/5-/images/image66.png)

 
小部件分组：上方左侧的下拉列表可以按照不同分组过滤小部件。

小部件搜索：上方右侧的搜索框可以匹配关键字母搜索小部件。

小部件授权状态：每个小部件下方的方框中显示已勾选的，表示该某个小部件是否已经授权。

授权与取消授权：在每个小部件下方的方框中勾选或者取消勾选，点击最右方〖保存〗后完成授权并返回小部件授权列表页面。

## 数据权限

应用平台涉及的权限管理应用是数据权限。在实际的业务里，都有一些敏感性的数据要控制，不是一般用户可以访问的，这就需要提供数据权限控制功能。

数据权限管理提供按照角色分配数据权限控制对象，以及对数据权限控制对象分配控制值，并提供取消分配控制值和批量取消功能。

点击管理中心主界面上的【数据权限】，进入数据权限管理界面，如下图所示：

![](/articles/appspecial/5-/images/image67.png)


 
左侧为对应角色。选中一个角色，点击〖分配对象〗，将角色分配给对象，本例中选择了组织为分配对象，如下图：

![](/articles/appspecial/5-/images/image68.png)


 
点击〖分配〗，选择一个或多个组织，按〖确定〗。也可以在〖搜索〗中输入对象名查询对象。

![](/articles/appspecial/5-/images/image69.png)


 
如果用户关联了这个角色，就只能看到这两条组织的数据。将鼠标放到每个对象的〖操作〗处，出现〖取消分配〗按钮，可以取消分配该对象；或者点击多个分配对象前的方框，然后按〖批量取消分配〗进行批量取消分配。
