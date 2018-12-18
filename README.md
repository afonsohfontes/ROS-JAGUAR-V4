# ROS-JAGUAR-V4
Repositorio com pacotes para controle do jaguar.

Tutorial para instalação dos pacotes:

0. criar workspace do Jaguar: http://wiki.ros.org/pt_BR/ROS/Tutorials/InstallingandConfiguringROSEnvironment
1. mover os pacotes para a pasta "src" do workspace e dar catkin_make. PS: Caso ocorram erros de arquivo ausente, mover conteudo a pasta "drr_jaguarv2_player" com arquivos .h para a pasta "devel/include" do workspace
2. dar source no workspace criado: "source ...devel/setup.bash"
3. Executando pacotes: rosrun tab tab para exibir todos os packages instalados 

PACOTES

dri_manipulator_arm_ctrl1: Pacote para controle do braço robótico modificado para inserção de cinemática e lógica de colisão

drrobotV2_player: Pacote com os nodes de controle do jaguar. Node drrobot_joy_teleop criado para realizar o controle do jaguar com o joystick. 
