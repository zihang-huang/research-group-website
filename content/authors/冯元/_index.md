---
# Display name
title: 冯元

# Full Name (for SEO)
first_name: 元
last_name: 冯

authors:
  - 冯元

# Is this the primary user of the site?
superuser: false

# Role/position
role: 教授，ACM Transactions on Software Engineering and Methodology 副编辑

# Organizations/Affiliations
organizations:
  - name: 清华大学
    url: ''

# Short bio (displayed in user profile at end of posts)
bio:

interests:
  - 量子模型检测
  - 量子程序验证
  - 量子通信并发系统

education:
  courses:
    - course: 本科
      institution: 清华大学应用数学系
      year: 1999
    - course: 博士
      institution: 清华大学计算机科学与技术系
      year: 2004

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:yuan_feng@tsinghua.edu.cn'
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''

# Highlight the author in author lists? (true/false)
highlight_name: false

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - 导师
---

### 研究概况

量子模型检测：经典模型检测是对顺序程序、并发协议、硬件系统进行形式化验证的一种重要技术。由于其可机械化和可以提供诊断信息，在工业界得到了广泛应用。我们提出了两种不同的量子马尔代夫链模型，并系统发展了线性和分支两种量子时序逻辑公式的模型检测方法。2021年，受剑桥大学出版社邀请，我们出版了《Model Checking Quantum Systems: Principles and Algorithms》，对量子模型检测这一新兴的研究方向，特别是我们课题组在这方面的工作进行了系统梳理。这是量子模型检测领域第一本学术专著。

量子程序验证：Hoare逻辑是程序验证的逻辑基础，在程序设计方法学中处于核心地位。Hoare逻辑通过为命令式编程语言的所有程序结构定义合适的公理和推理规则，使得该语言下程序的正确性都可以进行(部分)自动化证明。我们建立了含经典变量的量子Hoare逻辑，证明其可靠性和相对完备性，并在文献中第一次成功的利用Hoare逻辑验证完整的Shor算法(ACM TQC 2021)。最近，我们进一步利用这种技术分别为不共享变量的量子并行程序(TCS 2022)、只含经典通信的分布式量子程序(ACM TOCL 2022)、含不确定性构造的量子程序(ASPLOS’23)设计了Hoare逻辑系统，并证明了它们的可靠性和相对完备性。

量子通信并发系统：量子通信和密码是量子信息领域目前最为成熟、在某些方面已经获得实际应用的技术。为了形式化描述量子通信网络、为量子网络软件和通信协议的形式化验证奠定理论基础，我们提出了量子进程代数qCCS (Information and Computation 2007)。更重要的是，我们成功的找到了一种刻画量子进程等价性的互模拟关系，并证明了其对于各种进程构造的同余性(POPL’11, ACM TOPLAS 2012)。我们后续的一系列工作，包括符号互模拟 (ACM TOCL 2014)、开互模拟(TCS 2012)和基于分布的互模拟(CONCUR 2015)等，极大的丰富了qCCS的基础理论，也增强了其描述和验证实际量子通信系统的能力。