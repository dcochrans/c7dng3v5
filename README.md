## Git算不算程序员的必备技能？ KZSC1

更新时间：2026-09-15 07:13:13.389

363gpz.hothairybushes.com
3bvsj5.hothairybushes.com
现在dev分支工作已完成，现在我们切换到主分支master上，继续查看readme.txt内容如下：
4d2ngq.kvb1992.com
Git算不算程序员的必备技能？
34hnyt.compasslandconsultants.com
3dfgmy.compasslandconsultants.com
3mztbx.hongyihualang.cn
首先我们先来查看下readme.txt内容，接着添加内容77777777，如下：
3icpt1.kvb1995.com
3sorwb.hongyihualang.cn
2wcmn2.kvb1982.com
34zthh.kvb1987.com
4a6ey6.kvb1980.com
2vxzgu.misturabela.com
3rojg1.kvb1990.com
git branch查看分支，会列出所有的分支，当前分支前面会添加一个星号。然后我们在dev分支上继续做demo，比如我们现在在readme.txt再增加一行 7777777777777
2r3ojn.kvb1981.com
git checkout dev
45c2au.inmolopez.com
git branch dev
45s40v.kvb1991.com
4hmn6f.kvb1992.com
3pl5pr.kvb1998.com
git checkout 命令加上 –b参数表示创建并切换，相当于如下2条命令
439ljd.kvb1987.com
Git算不算程序员的必备技能？
306odu.kvb1979.com
2lhcpe.hoodamath2.com
2t3sv6.hothairybushes.com
3o3cqt.hongyihualang.cn
3v7k3z.kvb1979.com
3hksd7.kvb1995.com
4iptgh.kvb1981.com
2z7ov3.misturabela.com
3jlb7h.ecvyksp.cn
3wgiir.kvb1990.com
首先，我们来创建dev分支，然后切换到dev分支上。如下操作：
3z0ji3.hoodamath2.com
2kz15r.compasslandconsultants.com
3dblpo.hothairybushes.com
在 版本回填退里，你已经知道，每次提交，Git都把它们串成一条时间线，这条时间线就是一个分支。截止到目前，只有一条时间线，在Git里，这个分支叫主分支，即master分支。HEAD严格来说不是指向提交，而是指向master，master才是指向提交的，所以，HEAD指向的就是当前分支。
2xj9o0.hoodamath2.com
30f639.inmolopez.com
六：创建与合并分支。
3vpav6.kvb1988.com
413mft.misturabela.com
Git算不算程序员的必备技能？
361340.inmolopez.com
331s59.kvb1985.com
3whhrz.kvb1981.com
3z0kj8.hoodamath2.com
34vwhs.hothairybushes.com
3w5to4.ecvyksp.cn
3tm921.kvb1986.com
44hzan.misturabela.com
2ur6x5.ecvyksp.cn
接着在我本地目录下 生成testgit2目录了，如下所示：
3rcmq1.kvb1995.com
3wrjzg.kvb1993.com
3mki0x.hoodamath2.com
Git算不算程序员的必备技能？
3c2qfc.hoodamath2.com
2z6ibk.hongyihualang.cn
4hnke1.kvb1988.com
41syuj.kvb1989.com
31ziol.inmolopez.com
现在，远程库已经准备好了，下一步是使用命令git clone克隆一个本地库了。如下所示：
2pzvko.hoodamath2.com
2qkcj1.ecvyksp.cn
3060cl.kvb1991.com
Git算不算程序员的必备技能？
3r7mwc.kvb1995.com
3dgxa7.kvb1987.com
4i2vte.kvb1999.com
4iemeq.kvb1985.com
如下，我们看到：
3ic7jd.hongyihualang.cn
Git算不算程序员的必备技能？
2tm3pk.kvb1993.com
首先，登录github，创建一个新的仓库，名字叫testgit2.如下：
3xzvkt.hothairybushes.com
2vl556.kvb1980.com
2ss568.misturabela.com
3rggjz.kvb1997.com
3k6xjb.kvb1998.com
328jhx.hoodamath2.com
现在我们想，假如远程库有新的内容了，我想克隆到本地来 如何克隆呢？
34w39a.kvb1996.com
2wzmta.hoodamath2.com
如何从远程库克隆？上面我们了解了先有本地库，后有远程库时候，如何关联远程库。
3hae3u.compasslandconsultants.com
把本地master分支的最新修改推送到github上了，现在你就拥有了真正的分布式版本库了。
2uuvvk.misturabela.com
2vtzia.misturabela.com
3ergmw.kvb1986.com
git push origin master
3sgf80.hongyihualang.cn
33cdcv.hoodamath2.com
2odzri.hoodamath2.com
2pisp4.inmolopez.com
347j3g.compasslandconsultants.com
3v88bo.hongyihualang.cn
2tv1s7.kvb1988.com
3u50b6.kvb1999.com
3ols8r.compasslandconsultants.com
从现在起，只要本地作了提交，就可以通过如下命令：
4ebe3s.kvb1985.com
3tao2x.kvb1993.com
3kgdzs.kvb1986.com
36r2pp.kvb1998.com
3grw1s.kvb1983.com
Git算不算程序员的必备技能？
2y3hxo.kvb1982.com
由于远程库是空的，我们第一次推送master分支时，加上了 –u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。推送成功后，可以立刻在github页面中看到远程库的内容已经和本地一模一样了，上面的要输入github的用户名和密码如下所示：
3ldgbs.misturabela.com
3b6zbe.kvb1989.com
3ax736.hoodamath2.com
把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。
2rhr5y.kvb1985.com
2t0f49.kvb1997.com
37esu7.misturabela.com
3xsitr.kvb1999.com
Git算不算程序员的必备技能？
3yuo19.kvb1982.com
3hcl9t.ecvyksp.cn
479y75.compasslandconsultants.com
40y6au.compasslandconsultants.com
46w74y.kvb1990.com
所有的如下：
48eu6d.hongyihualang.cn
git remote add origin
41bfc0.kvb1981.com
现在，我们根据GitHub的提示，在本地的testgit仓库下运行命令：
2vwdpj.kvb1979.com
403snd.inmolopez.com
目前，在GitHub上的这个testgit仓库还是空的，GitHub告诉我们，可以从这个仓库克隆出新的仓库，也可以把一个已有的本地仓库与之关联，然后，把本地仓库的内容推送到GitHub仓库。
42q3ol.inmolopez.com
3cmywm.kvb1991.com
3a67hb.inmolopez.com
3l0qnv.hoodamath2.com
30jsdf.hothairybushes.com
477tvi.inmolopez.com
Git算不算程序员的必备技能？
40g7wt.hothairybushes.com
4584r4.kvb1978.com
2u0ycm.hothairybushes.com
在Repository name填入testgit，其他保持默认设置，点击“Create repository”按钮，就成功地创建了一个新的Git仓库：
3knysi.kvb1989.com
485ryy.misturabela.com
3e0n2s.kvb1989.com
3znfjn.kvb1999.com
Git算不算程序员的必备技能？
39whui.kvb1997.com
3afce4.ecvyksp.cn
4967b1.kvb1980.com
首先，登录github上，然后在右上角找到“create a new repo”创建一个新的仓库。如下：
4gbrva.kvb1993.com
现在的情景是：我们已经在本地创建了一个Git仓库后，又想在github创建一个Git仓库，并且希望这两个仓库进行远程同步，这样github的仓库可以作为备份，又可以其他人通过该仓库来协作。
37op9l.compasslandconsultants.com
33sffh.misturabela.com
如何添加远程库？
419bb1.kvb1981.com
Git算不算程序员的必备技能？
406qin.hothairybushes.com
3dq0a9.hongyihualang.cn
点击 Add Key，你就应该可以看到已经添加的key。
3zdqim.hoodamath2.com
3lurcr.cdroutlet.com
3n8a1p.kvb1999.com
40mzxd.inmolopez.com
3xpft9.hoodamath2.com
2zmbe2.cdroutlet.com
419yof.kvb1989.com
4id0iy.kvb1992.com
Git算不算程序员的必备技能？
4gquwv.kvb1998.com
第二步：登录github,打开” settings”中的SSH Keys页面，然后点击“Add SSH Key”,填上任意title，在Key文本框里黏贴id_rsa.pub文件的内容。
39jpo1.cdroutlet.com
id_rsa是私钥，不能泄露出去，id_rsa.pub是公钥，可以放心地告诉任何人。
3svyko.cdroutlet.com
4e0mz9.kvb1989.com
2rr302.misturabela.com
4bjorm.kvb1981.com
2qt8iz.kvb1990.com
3rvoxy.cdroutlet.com
33kx0f.hongyihualang.cn
Git算不算程序员的必备技能？
3sxito.kvb1988.com
ssh-keygen -t rsa –C “youremail@example.com”, 由于我本地此前运行过一次，所以本地有，如下所示：
45xt8q.hongyihualang.cn
2sc12g.ecvyksp.cn
2rs47w.hongyihualang.cn
2zbwvc.cdroutlet.com
3ahrwm.hothairybushes.com
第一步：创建SSH Key。在用户主目录下，看看有没有.ssh目录，如果有，再看看这个目录下有没有id_rsa和id_rsa.pub这两个文件，如果有的话，直接跳过此如下命令，如果没有的话，打开命令行，输入如下命令：
38fzaz.kvb1997.com
3k0446.kvb1995.com
在了解之前，先注册github账号，由于你的本地Git仓库和github仓库之间的传输是通过SSH加密的，所以需要一点设置：
44iv9h.compasslandconsultants.com
4a0amb.misturabela.com
五：远程仓库。
3hbwa3.hothairybushes.com
2t2x6i.kvb1999.com
3k7s98.hongyihualang.cn
3mmmw2.inmolopez.com
Git算不算程序员的必备技能？
3j80cy.kvb1991.com
432qo0.compasslandconsultants.com
再来看看我们testgit目录，添加了3个文件了。如下所示：
3opvab.kvb1996.com
Git算不算程序员的必备技能？
2v6ec1.kvb1985.com
可以使用如下命令 git checkout -- b.txt，如下所示：
2s6z5p.ecvyksp.cn
2ukme3.kvb1985.com
33ke3z.misturabela.com
只要没有commit之前，如果我想在版本库中恢复此文件如何操作呢？
48oc5f.hongyihualang.cn
4734m8.kvb1978.com
Git算不算程序员的必备技能？
3x2lwj.hoodamath2.com
3pwbvn.kvb1998.com
34nlyf.kvb1986.com
2mxe8s.ecvyksp.cn
33idmd.hoodamath2.com
4ghjqd.kvb1998.com
如上：一般情况下，可以直接在文件目录中把文件删了，或者使用如上rm命令：rm b.txt ，如果我想彻底从版本库中删掉了此文件的话，可以再执行commit命令 提交掉，现在目录是这样的，
3mf0sl.misturabela.com
3mp3zi.kvb1988.com
2l4w2y.ecvyksp.cn
39o2ns.compasslandconsultants.com
3nj6fp.misturabela.com
42kv0w.kvb1997.com
Git算不算程序员的必备技能？
4av9o2.kvb1997.com
假如我现在版本库testgit目录添加一个文件b.txt,然后提交。如下：
2pxy2o.kvb1995.com
2yc1cx.inmolopez.com
二：删除文件。
3g9s0b.hoodamath2.com
注意：命令git checkout -- readme.txt 中的 -- 很重要，如果没有 -- 的话，那么命令变成创建分支了。
3b1ci3.kvb1982.com
Git算不算程序员的必备技能？
46ioso.kvb1983.com
对于第二种情况，我想我们继续做demo来看下，假如现在我对readme.txt添加一行 内容为6666666666666，我git add 增加到暂存区后，接着添加内容7777777，我想通过撤销命令让其回到暂存区后的状态。如下所示：
4i0eds.kvb1985.com
3hxds5.hongyihualang.cn
3sc6i0.kvb1998.com
2.另外一种是readme.txt已经放入暂存区了，接着又作了修改，撤销修改就回到添加暂存区后的状态。
4gc39x.kvb1986.com
3kqvpr.kvb1987.com
1.readme.txt自动修改后，还没有放到暂存区，使用 撤销修改就回到和版本库一模一样的状态。
49rop5.inmolopez.com
命令 git checkout --readme.txt 意思就是，把readme.txt文件在工作区做的修改全部撤销，这里有2种情况，如下：
44b29s.kvb1992.com
3s12r4.misturabela.com
2lzt79.compasslandconsultants.com
Git算不算程序员的必备技能？
3ilech.kvb1995.com
47yi58.hongyihualang.cn
300xpm.kvb1989.com
2ytmfu.kvb1996.com
38q8uw.ecvyksp.cn
git checkout -- readme.txt,如下所示：
3ghkf0.hothairybushes.com
3uu8gq.hongyihualang.cn
可以发现，Git会告诉你，git checkout -- file 可以丢弃工作区的修改，如下命令：
2oyxvr.hothairybushes.com
346yy1.inmolopez.com
3t20lo.kvb1996.com
Git算不算程序员的必备技能？
3r8m3i.hongyihualang.cn
但是现在我不想使用上面的2种方法，我想直接想使用撤销命令该如何操作呢？首先在做撤销之前，我们可以先用 git status 查看下当前的状态。如下所示：
3hz5ue.cdroutlet.com
47l1oh.inmolopez.com
3wildv.kvb1985.com
2l78q5.cdroutlet.com
45lkc3.hoodamath2.com
第二：我可以按以前的方法直接恢复到上一个版本。使用 git reset --hard HEAD^
3p0lt0.kvb1986.com
第一：如果我知道要删掉那些内容的话，直接手动更改去掉那些需要的文件，然后add添加到暂存区，最后commit掉。
3gyy4h.kvb1996.com
41xlqa.hoodamath2.com
3gxf19.kvb1988.com
在我未提交之前，我发现添加5555555555555内容有误，所以我得马上恢复以前的版本，现在我可以有如下几种方法可以做修改：
40jmsb.kvb1998.com
Git算不算程序员的必备技能？
2odhiw.hothairybushes.com
2vxwb3.hongyihualang.cn
34nfq7.kvb1983.com
比如我现在在readme.txt文件里面增加一行 内容为555555555555，我们先通过命令查看如下：
439is4.hothairybushes.com
3vow1e.misturabela.com
一：撤销修改：
4c6toe.kvb1987.com
351inn.hothairybushes.com
2n264b.compasslandconsultants.com
3ckv9k.inmolopez.com
四：Git撤销修改和删除文件操作。
2vi7yv.kvb1992.com
Git算不算程序员的必备技能？
3tpft5.misturabela.com
3nkt09.kvb1978.com
接着我们可以使用git commit一次性提交到分支上，如下：
2nyorj.inmolopez.com
Git算不算程序员的必备技能？
2xuqu1.kvb1988.com
3a57wd.hoodamath2.com
2t0as5.kvb1979.com
现在我们先使用git add 命令把2个文件都添加到暂存区中，再使用git status来查看下状态，如下：
39wugn.kvb1990.com
3plh4n.compasslandconsultants.com
2t3uaj.hothairybushes.com
2r5npc.ecvyksp.cn
3rzryw.ecvyksp.cn
2wj2pm.kvb1996.com
3sgliv.kvb1980.com
3vom5c.compasslandconsultants.com
33rrga.hothairybushes.com
481uln.hongyihualang.cn
355za0.ecvyksp.cn
Git算不算程序员的必备技能？
3y4dmy.kvb1993.com
我们在readme.txt再添加一行内容为4444444，接着在目录下新建一个文件为test.txt 内容为test，我们先用命令 git status来查看下状态，如下：
3tb7is.hoodamath2.com
478brb.kvb1998.com
我们继续使用demo来演示下：
47nad7.kvb1982.com
3c15lj.hothairybushes.com
第二步：使用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支上。
308lpw.inmolopez.com
4a3j9h.cdroutlet.com
第一步：是使用 git add 把文件添加进去，实际上就是把文件添加到暂存区。
3u13ja.kvb1985.com
3vwxj8.kvb1983.com
3bv27t.kvb1996.com
36pt24.hongyihualang.cn
3j10is.kvb1992.com
3u9qhg.kvb1988.com
32omoq.hoodamath2.com
我们前面说过使用Git提交文件到版本库有两步：
44utnz.hothairybushes.com
3vfu6m.kvb1993.com
2toh61.misturabela.com
版本库(Repository)：工作区有一个隐藏目录.git,这个不属于工作区，这是版本库。其中版本库里面存了很多东西，其中最重要的就是stage(暂存区)，还有Git为我们自动创建了第一个分支master,以及指向master的一个指针HEAD。
4ilxti.kvb1987.com
2wo6ta.kvb1986.com
4a3mkj.kvb1978.com
工作区：就是你在电脑上看到的目录，比如目录下testgit里的文件(.git隐藏目录版本库除外)。或者以后需要再新建的目录文件等等都属于工作区范畴。
3xayv4.kvb1979.com
3wjbmz.kvb1983.com
3grauv.kvb1981.com
三：理解工作区与暂存区的区别？
2wb1pc.kvb1999.com
可以看到 目前已经是最新的版本了。
43z9po.compasslandconsultants.com
3yryjf.kvb1992.com
3opugs.hothairybushes.com
2stt9y.kvb1982.com
Git算不算程序员的必备技能？
36eezj.kvb1990.com
git reset --hard 6fcfc89来恢复了。演示如下：
2srkl4.hongyihualang.cn
3dqp4t.hongyihualang.cn
3l9kd7.hothairybushes.com
通过上面的显示我们可以知道，增加内容3333的版本号是 6fcfc89.我们现在可以命令
359w7u.hoodamath2.com
Git算不算程序员的必备技能？
39zmwh.misturabela.com
git reset --hard 版本号 ，但是现在的问题假如我已经关掉过一次命令行或者333内容的版本号我并不知道呢？要如何知道增加3333内容的版本号呢？可以通过如下命令即可获取到版本号：git reflog 演示如下：
4bs4rr.kvb1982.com
2nzf1m.compasslandconsultants.com
3qfkwh.kvb1998.com
我们看到 增加333333 内容我们没有看到了，但是现在我想回退到最新的版本，如：有333333的内容要如何恢复呢？我们可以通过版本号回退，使用命令方法如下：
3w884b.kvb1985.com
3rftne.kvb1979.com
3vhl8t.cdroutlet.com
2ufx1f.compasslandconsultants.com
Git算不算程序员的必备技能？
2zj31v.compasslandconsultants.com
48hya7.compasslandconsultants.com
3vbfq2.kvb1999.com
38hmbk.kvb1987.com
3k7muz.cdroutlet.com
2wtayw.compasslandconsultants.com
401coq.compasslandconsultants.com
可以看到，内容已经回退到上一个版本了。我们可以继续使用git log 来查看下历史记录信息，如下：
433fu5.hoodamath2.com
4i7yn1.kvb1980.com
2rc731.kvb1986.com
Git算不算程序员的必备技能？
46vnny.kvb1990.com
3csy48.kvb1980.com
3owljh.hongyihualang.cn
40ka2q.ecvyksp.cn
3notvm.inmolopez.com
3ezsh8.kvb1999.com
再来查看下 readme.txt内容如下：通过命令cat readme.txt查看
3dc67u.kvb1991.com

---

# c7dng3v5
Auto-created repository for publishing - 2026-09-15T07:13:07.254Z
