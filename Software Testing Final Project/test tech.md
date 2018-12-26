### 1、按是否查看程序内部结构分为：

- **黑盒测试**（black-box testing）：只关心输入和输出的结果
- **白盒测试**（white-box testing）：去研究里面的源代码和程序结构

### 2、按是否运行程序分为：

- **静态测试**（static testing）：是指不实际运行被测软件，而只是静态地检查程序代码、界面或文档可能存在的错误的过程。静态测试包括：对于代码测试，主要是测试代码是否符合相应的标准和规范。对于界面测试，主要测试软件的实际界面与需求中的说明是否相符。对于文档测试，主要测试用户手册和需求说明是否真正符合用户的实际需求。
- **动态测试**（dynamic testing），是指实际运行被测程序，输入相应的测试数据，检查输出结果和预期结果是否相符的过程

### 3、按阶段划分：

- **单元测试（unit testing）**，是指对软件中的最小可测试单元进行检查和验证。桩模块（stud）是指模拟被测模块所调用的模块，驱动模块（driver）是指模拟被测模块的上级模块，驱动模块用来接收测试数据，启动被测模块并输出结果。

- **集成测试（integration testing）**，是单元测试的下一阶段，是指将通过测试的单元模块组装成系统或子系统，再进行测试，重点测试不同模块的接口部门。集成测试就是用来检查各个单元模块结合到一起能否协同配合，正常运行。

- **系统测试（system testing）**，指的是将整个软件系统看做一个整体进行测试，包括对功能、性能，以及软件所运行的软硬件环境进行测试。

  **系统测试（system testing）**，指的是将整个软件系统看做一个整体进行测试，包括对功能、性能，以及软件所运行的软硬件环境进行测试。
  系统测试的主要依据是《系统需求规格说明书》文档。

- **验收测试（acceptance testing）**，指的是在系统测试的后期，以用户测试为主，或有测试人员等质量保障人员共同参与的测试，它也是软件正式交给用户使用的最后一道工序。验收测试又分为a测试和beta测试，其中a测试指的是由用户、 测试人员、开发人员等共同参与的内部测试，而beta测试指的是内测后的公测，即完全交给最终用户测试。

### 4、黑盒测试分为功能测试和性能测试：

- **功能测试**（function testing），是黑盒测试的一方面，它检查实际软件的功能是否符合用户的需求。包括逻辑功能测试（logic function testing）界面测试（UI testing）UI=User Interface易用性测试（usability testing）：是指从软件使用的合理性和方便性等角度对软件系统进行检查，来发现软件中不方便用户使用的地方。兼容性测试（compatibility testing）：包括硬件兼容性测试和软件兼容性测试
- **性能测试**（performance testing）：软件的性能主要有时间性能和空间性能两种:时间性能：主要指软件的一个具体事务的响应时间（respond time）。空间性能：主要指软件运行时所消耗的系统资源。
- 软件性能测试分为：
  - 一般性能测试：指的是让被测系统在正常的软硬件环境下运行，不向其施加任何压力的性能测试。
  - 稳定性测试也叫可靠性测试（reliability testing）：是指连续运行被测系统检查系统运行时的稳定程度。
  - 负载测试（load testing）：是指让被测系统在其能忍受的压力的极限范围之内连续运行，来测试系统的稳定性。
  - 压力测试（stress testing）：是指持续不断的给被测系统增加压力，直到将被测系统压垮为止，用来测试系统所能承受的最大压力。(Validate the system or software can allowed the biggest stress.)

### 5、其他测试类型：

- **回归测试**（regression testing）是指对软件的新的版本测试时，重复执行上一个版本测试时的用例。(When a new build or release is deployed, repeat all the test cases which has executed in the last build or release.)
- **冒烟测试**（smoke testing），是指在对一个新版本进行大规模的测试之前，先验证一下软件的基本功能是否实现，是否具备可测性。(validate the major function is deployed or not in software of system when a new build or release is implement.)
- **随机测试**（random testing），是指测试中所有的输入数据都是随机生成的，其目的是模拟用户的真实操作，并发现一些边缘性的错误。(means or all the test data is random, to validate the some edge bugs.)


- ​

- ------

  **IEBT 直觉和经验**

- **IDBT 基于输入域**

- **组合测试方法**

- **CoBT 基于代码**

  - 控制流覆盖
    - 逻辑
    - 基本路径

- **MBT 基于模型**

  - 随机测试 monkey

- **基于需求的**

