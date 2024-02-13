<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-name" class="anchor" aria-hidden="true" tabindex="-1" href="#name"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">姓名</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mips-cpu - 用 Verilog 编写的 MIPS CPU</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-description" class="anchor" aria-hidden="true" tabindex="-1" href="#description"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用 Verilog 编写的 MIPS CPU 的实现。该项目还处于非常早期的阶段，目前仅实现了 MIPS CPU 的最基本功能。</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">32位MIPS处理器</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用 Verilog 实现</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5级流水线</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">静态分支未采用分支预测器</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解码中的分支检测（第 2 阶段）</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持停顿以避免写入后读取（RAW）和其他危险</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以从内存转发（第 4 阶段）并写回（第 5 阶段）以避免停&ZeroWidthSpace;&ZeroWidthSpace;顿</font></font></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大部分设计的灵感来自 David A. Patterson 和 John L. Hennessy 所著的《计算机组织与设计》一书（2008 年第 4 版）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目还包括全套测试台。这些对于快速检查以验证新的更改没有破坏之前工作的功能来说是非常宝贵的。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-requirements" class="anchor" aria-hidden="true" tabindex="-1" href="#requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目需要 Verilog 模拟器，例如</font></font><a href="http://iverilog.icarus.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Icarus</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、Gcc 编译器和 Gcc MIPS 交叉编译器。要检查您的系统是否安装了所需的程序，请运行该</font></font><code>check-install.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
脚本。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ ./check-install.sh
Checking for required programs...
  mips-linux-gnu-objcopy
  mips-linux-gnu-as
  iverilog
Please install the missing programs and retry.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ ./check-install.sh
Checking for required programs...
  mips-linux-gnu-objcopy
  mips-linux-gnu-as
  iverilog
Please install the missing programs and retry." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h1 tabindex="-1" dir="auto"><a id="user-content-running-test-benches" class="anchor" aria-hidden="true" tabindex="-1" href="#running-test-benches"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行测试台</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试位于</font></font><code>verilog/test/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中。一切都是使用命令构建和运行的</font></font><code>make</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>make
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="make" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个测试有两个部分：Verilog 代码和汇编代码。 Verilog 代码使用通用 CPU 测试平台 ( </font></font><code>cpu_tb.v</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)，使用特定的汇编 .hex 文件构建特定测试。 .hex 文件是通过使用 Gcc MIPS 交叉编译器汇编 .asm 文件并将其转换为适合 Verilog 使用的 ASCII 十六进制来生成的。然后，可以使用</font></font><a href="http://iverilog.icarus.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Icarus Verilog</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等模拟器运行 Verilog 代码
</font><font style="vertical-align: inherit;">来执行汇编指令并生成其输出转储 (.out)。最后，可以将输出文件 (.out) 与已知良好的输出文件 (.check) 进行比较，以查看是否存在任何差异。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关这些步骤的更多信息，请参阅 中的 Makefile </font></font><code>verilog/test/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-author" class="anchor" aria-hidden="true" tabindex="-1" href="#author"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作者</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">耶利米·马勒</font></font><a href="mailto:jmmahler@gmail.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">jmmahler@gmail.com </font></font></a><br>
<a href="http://github.com/jmahler"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://github.com/jmahler</font></font></a></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-copyright" class="anchor" aria-hidden="true" tabindex="-1" href="#copyright"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版权</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版权所有 © 2015，耶利米·马勒。版权所有。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
该项目是免费软件，并根据</font></font><a href="http://www.gnu.org/licenses/gpl.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GNU 通用公共许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布。</font></font></p>
</article></div>
