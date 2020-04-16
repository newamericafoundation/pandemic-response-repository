---
title: Why OSS
layout: page
permalink: /why-oss/
---

# What is open source software?

Open source software means that the human-readable source code is available to the public for others to use, copy, learn from, and modify for their benefits. All kinds of software can be open source, from operating systems and under-the-hood utilities to web browsers and user-facing apps. The majority of the world’s software is open source, and some estimates say that nearly all software has some open source components to it. Chances are high that your organization is already using open source software, either directly or through other software that depends on it.

While open source software (OSS) can, at a bare minimum, simply mean releasing the source code publicly, the underlying principles of open source go further than that. In the case of public sector products, OSS is at the core of reuse. For organizations who wish to create something that others can reuse easily, it is fundamental to adhere to open source principles.  Note that “open source is different than “coding in the open.” fCoding in the open means publishing the source code of a system or application without taking care to ensure its reusability. Open source aspires to something larger: software that is not only available for reuse, but built and maintained to ensure reusability.

Open source software is released with specific licenses that outline the permitted usage of the source code. Not all open source code can be used in any fashion. When using open source tools, it is important to review the license to ensure you abide by its allowances and restrictions. When opening your own resources, it’s critical to provide a license that makes clear what the resources can be used for. Common licenses are reused across many open source projects, such as the [MIT license](https://opensource.org/licenses/MIT) or the [GPL license](https://opensource.org/licenses/gpl-license). By using common licenses, projects reduce the burden of understanding unique license terms and provide clear and well-understood terms to the use of their resources.

# Why Use Open Source?

The benefits of using open source principles is well understood and documented by the software community. Anna Shipman, former Open Source Lead with the UK’s Government Digital Service, [articulated an excellent set of benefits](https://gds.blog.gov.uk/2017/09/04/the-benefits-of-coding-in-the-open/) for open sourcing your own work

## Encourages good practice

To expand on this list, open sourcing work encourages good practice by creating public accountability. If everyone can see something it has to be good enough to release to the public right from the start. The quality of the work, its documentation, code reviews, and other factors are all held to a high standard, encouraging best practices. Open source also brings critical considerations, such as security, software design, documentation, processes, and even ownership, immediately to the forefront, rather than allowed to delay over time. 

## Simplifies Collaboration

Collaboration is simplified when all of the work is done in the open, as there are no required special approvals or agreements for code to be shared. In the current closed-source state, two different teams at the same government agency might require months of time to secure the approvals necessary to share work. If this work was open already, the collaboration could have started immediately. Inviting people to collaborate on open-source projects is much simpler, as the work to open it up broadly has already been done.

## Fosters Growth of Similar Solutions

When the work you are doing is made available openly, interested parties can not only collaborate, but can also iterate and learn from your work. Others can use your work as a starting point to find creative and novel uses of the same components. Often, these novel uses can directly benefit your work as well, as third parties can solve problems that you hadn’t yet prioritized, or can make existing features more robust. By open sourcing the work, you create the opportunity for creative expansion on top of what has already been done.

## Increases Government Transparency

The benefit of transparency goes beyond creating accountability – it’s also a core part of working on public services. The public should be able to see the work that their government is doing on services for their benefit. Improving transparency makes it clear that progress is being made on important services and issues, and keeps the public informed on future plans as well. Open sourcing work encourages active feedback and participation from public stakeholders, who can now view the progress as it happens and hold more confidence in the work. As the [Department of the Interior](https://18f.gsa.gov/2018/05/24/what-agencies-have-to-say-about-working-in-the-open/) puts it, “By using open software and working in the open, you remove barriers to critical evaluation and participation from others. Inviting critique from others can be uncomfortable, but it increases the likelihood that the final product is more effective at meeting the needs of multiple stakeholders inside and outside government.”

Many of these benefits carry over when using existing open source tools, as well. By bringing open source tools into your organization, you build off of a foundation that has community support, that is already transparent, and that enables clear collaboration right from the start. Additionally, you can see how all of the pieces of the existing open source tools work, and make modifications to it to fit your specific needs. Nothing is kept proprietary or hidden – instead, all of the code for these services is made available for review by third parties, including your own organization.

## More Sustainable Tools; Less Vendor-Dependence

Using open source technologies also leads to more sustainable tools that are less dependent on proprietary, locked software. Using and developing open source software, along with open standards, greatly improves the flexibility of your organization by allowing you to change vendors, move the software to different parts of the organization, and use or reuse as much of the software as needed. Open source software guarantees that your organization, and the public, have full access to the source code without needing any permissions from the vendor. 

Note that regardless of whether you open source your own tools, or use existing open source tools, you are still ultimately responsible for the service. Using open source software does not put the onus on other maintainers – as the service owner, that still falls on your shoulders. For example, you still hold the responsibility of ensuring security, or meeting users needs. However, using open source tools makes each of these easier to achieve, and does enable a community of like-minded service providers to support each other in achieving their goals.

## Cost effective

Open source software is free to use. You can copy and use the source code without payment to the original creators, and use it in whatever way you would like (consistent with the software license). However, this doesn’t mean that there are zero costs associated with using open source. While the code itself is free and open, there are other considerations to make, most of which are consistent regardless of whether you are using open source tools or building your own software.

Even though the software itself is free, it still  costs money to host the software on a server. Additionally, there are costs to maintain the source code, such as bringing in talent with the necessary skills to copy and modify the source code, create your own running system from it, and maintain it with updated security patches. This need for talent is a relative constant whether you chose to use open source tools or contract with a closed-source vendor. The key difference is that when purchasing a closed-source proprietary system, that talent and the skills and knowledge they gain will stay with the vendor, rather than becoming a part of your organization.

Open sourcing your own code does not mean you will receive free labor on your system. You still ultimately own and maintain the system, and to the extent that a community forms around your system, you need to build and manage that community. The contributors are, after all, other people, whowill want to work on the project because of some benefit they can take from it. Building the community grants many benefits, and while there is not any expectation that the community will be compensated for contributions, creating an environment where a community can thrive requires effort. We discuss community building and management later in this guide.

# Concerns

## Security

There is a common misconception that open source software is inherently less secure than proprietary software, due to the source code being available to the public. This argument relies on the assumption that an obscure piece of software is secure simply because not many people know it exists. However, [the consensus in the security space](https://dodcio.defense.gov/open-source-software-faq/#Q:_Doesn.27t_hiding_source_code_automatically_make_software_more_secure.3F) is that relying on obscuring code for the sake of security actually introduces more security risks, as obscured code cannot be assessed by third parties on whether it follows security best practices. Obscurity also allows vulnerabilities to exist in the codebase in an unknown or undisclosed state. In short, when software relies on obscurity to enforce security, it assumes that potential attackers don’t have other means to find and access vulnerabilities – which they regularly do.

The security community holds that open source software is more secure than closed software. The source code can be regularly reviewed by third parties, including automated and manual review by security experts. By not relying on security through obscurity, more diligent security practices are generally used, including rapid security patches and separation of sensitive information. Designing the codebase with the assumption that it will be made public inherently leads to more secure systems, as it makes access to the code table stakes for ensuring security.

There are certain security practices that do need to be followed when open sourcing software, many of which are best practices regardless of whether the source code is open or not. Most critical to this is that passwords, keys, credentials, and other secret information must not be included in the source code. Too often, code repositories will have the passwords for different systems coded into them. This is a simple problem to solve using existing tools, many of which are open source themselves. This type of secret information can be kept separate from the codebase, and accessed by the code when needed.

This principle – that secret information is kept separate from the source code – also applies to privacy concerns with open source software. The source code should not include any user data in it. Furthermore, having access to the source code should not grant someone the ability to access user data. These are simple things to ensure with good engineering practices, and ensure that the privacy of user data is maintained while the source code is made open.

Again, the UK’s Government Digital Service provides a great set of guidance on security considerations, which you can access [here](https://www.gov.uk/government/publications/open-source-guidance/security-considerations-when-coding-in-the-open).

## Fraud Detection Services

Aside from the need to keep certain secret information (eg. keys, credentials) closed from the source code, some also argue that fraud detection services should be closed, as those systems need to stay ahead of potential fraud. However, this argument should not be interpreted to mean that any decision-making algorithms should be kept secret. The belief that people might be able to game a system if they know it tends to be false, with the exception of fraud algorithms. In many cases, knowing the algorithms does not let people game the system if they don’t also have the configuration or data behind it, which should be kept secret. Similarly, the risk of decision-making systems being gamed is very low when the decisions being coded  f existing public policy.

## Future Policies

Note that code that implements yet-to-be-released policy should remain closed, as the policy should be made public before any software implementation details potentially complicate the release of the policy. Government policies tend to follow particular paths to being released, and while it can be very valuable to work on the systems to implement the policies ahead of time, they should only be released once the policy is made public. A more detailed resource for what should remain closed can be found [here](https://www.gov.uk/government/publications/open-source-guidance/when-code-should-be-open-or-closed).

## Navigating Licenses

Aside from the risks of the open code itself, there are other potential risks when it comes to misinterpretation or misuse of licenses. The open source software license ecosystem is robust, mature, and well understood. Many resources exist to support navigating the licenses, and there are technical legal experts that can assist with the interpretation of common and uncommon licenses. The risk here is small, and generally amounts to whether or not attribution must be given, or how your systems much themselves be licensed when using other systems.

# Policy & Open Source

Teams within an organization often find paths to creating and using open source on their own. The creation of organization-wide open source policy for building and using open source would not only clear the path for these efforts, but also provide consistent processes that can be followed across the organization. Policy that makes clear that open source software is allowed and encouraged, and that provides a process for opening software and for bringing in open source software, goes a long way toward increasing open source usage within organizations.

In particular, providing legal clarity and consistency provides a huge benefit, as one of the larger hurdles with organization-wide open source is the variable interpretations of open source licenses. These licenses can vary from straightforward to complex, and the interpretations can vary depending on the technical proficiency and risk attitude of the legal counsel involved. Creating a consistent interpretation of the legality of open source software will smooth use and access to it across the board.