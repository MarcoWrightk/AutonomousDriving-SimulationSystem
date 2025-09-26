# Deployment Strategy

This folder contains all configuration files, scripts, and orchestration tools required to deploy the AutonomousDriving-SimulationSystem across local, edge, and cloud environments.

### Supported Targets
- Local Docker
- Nvidia DRIVE AGX Xavier
- AWS EC2 + S3
- GCP Compute Engine
- AirSim, Simulink, ROS

### Components
- `Dockerfile`: Base image for simulation modules
- `docker-compose.yml`: Multi-service orchestration
- `jenkins_pipeline.groovy`: CI/CD automation
- `deploy.sh`: Manual deployment script
- `prometheus_config.yml`: Real-time metrics
- `ros_launch/`: ROS node orchestration
- `airsim_bridge/`: Unreal Engine integration
