# ROSCon 2024 Workshop: Demystifying ROS 2 Networking

> [!IMPORTANT]  
For this workshop, you will need a way to run ROS 2 Humble with a desktop environment.  There are a few options for this but using a Virtualbox virtual machine is recommend as it has everything pre-installed.

> [!TIP]
> Watch this repository to get notified of updates.

## Setup

### Virtualbox

- Virtualbox can be installed on Windows/macOS/Linux using the instructions here: https://www.virtualbox.org/wiki/Downloads
- No need to install the VirtualBox Extension Pack.
- Download the virtual machine from (warning 10GB download): https://drive.google.com/file/d/1Da5Xe49RaEhADSNuUyq481WLAx81efdk/view?usp=sharing
- The sha256sum is `97f7c35d02e9306253af11838294500f6a57c31e63071f4c6fbc67656de6f17c`
- Import the virtual machine into into Virtualbox.
- The login credentials:
  - user: `robot`
  - password: `clearpath`
- Use `sudo hostnamectl set-hostname NEW_HOSTNAE_HERE` to change to an unique name.
- Update the workshop repo using: `cd roscon2024-workshop-demystifying-ros2-networking; git pull`

### Other setup

The following packages are used for the workshop:

- iperf3
- nmap
- ssh
- wireshark
- python3-rosdep
- ros-dev-tools
- ros-humble-desktop (Install ROS 2 Humble: https://docs.ros.org/en/humble/Installation.html)
- ros-humble-turtlebot4-desktop
- git repo `roscon2024-workshop-demystifying-ros2-networking` (`git clone https://github.com/clearpathrobotics/roscon2024-workshop-demystifying-ros2-networking.git`)
- docker-ce (Install docker: https://docs.docker.com/engine/install/)
- ZettaScale container image: (Pull using `docker pull zettascaletech/roscon2024_workshop`)
