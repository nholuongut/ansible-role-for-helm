# Ansible Role: Helm
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This role installs the [Helm](https://helm.sh) binary on any supported host.

## Requirements

N/A

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    helm_version: 'v3.2.1'
    helm_platform: linux
    helm_arch: amd64

Controls for the version of Helm to be installed. See [available Helm releases](https://github.com/helm/helm/releases/). You can upgrade or downgrade versions by changing the `helm_version`.

    helm_repo_path: "https://get.helm.sh"

The path to the main Helm repo. Unlessy you need to override this for special reasons (e.g. running on servers without public Internet access), you should leave it as the default.

    helm_bin_path: /usr/local/bin/helm

The location where the Helm binary will be installed.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - role: nholuong.helm

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
