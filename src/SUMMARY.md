## User documentation

- [Introduction](introduction.md)

- [Quick Start](tutorials/quickstart.md)

- [Installation](installation/installation.md)
  - [Install Epinio](installation/installation.md)
  - [Install Epinio cli](installation/install_epinio_cli.md)
  - [Install Epinio with custom DNS](installation/install_epinio_customDNS.md)
  - [Install Epinio with "magic" DNS](installation/install_epinio_magicDNS.md)
  - [Uninstall Epinio](installation/uninstall_epinio.md)

- [Explanations](explanations/explanations.md)

  - [Advanced topics](explanations/advanced.md)
  - [Detailed Push Process](explanations/detailed-push-process.md)
  - [Principles](explanations/principles.md)
  - [Security](explanations/security.md)

- [HowTos](howtos/howtos.md)

  - [Certificate Issuers](howtos/certificate_issuers.md)
  - [Provision external IP address for local Kubernetes](howtos/provision_external_ip_for_local_kubernetes.md)
  - [Push with gitjob](howtos/gitjob_push.md)
  - [Setup external S3 storage](howtos/setup_external_s3.md)
  - [Setup external container registry](howtos/setup_external_registry.md)
  - [Port Forwarding](howtos/port_forwarding.md)
  - [Custom Routes](howtos/custom_routes.md)
  - [Install Epinio on RKE2 (Rancher)](howtos/install_epinio_on_rke.md)
  - [Install Epinio on K3s (local)](howtos/install_epinio_on_k3s.md)
  - [Install Epinio on Rancher Desktop (local)](howtos/install_epinio_on_rancher_desktop.md)
  - [Install Epinio on K3d (local)](howtos/install_epinio_on_k3d.md)
  - [Install Epinio on Minikube (local)](howtos/install_epinio_on_minikube.md)
  - [Install Epinio on Public Clouds](howtos/install_epinio_on_public_cloud.md)
  - [Install Wordpress on Epinio](howtos/install_wordpress_application.md)

- [Reference documentation](references/references.md)

  - [System Requirements](references/system_requirements.md)
      - [Windows](references/windows.md)
  - [Command requirements](references/README.md)
  - [Command reference](references/commands.md)

    - [epinio](references/cli/epinio.md)

      - [epinio_app](references/cli/epinio_app.md)

        - [epinio_app_create](references/cli/epinio_app_create.md)
        - [epinio_app_delete](references/cli/epinio_app_delete.md)
        - [epinio_app_env](references/cli/epinio_app_env.md)

          - [epinio_app_env_list](references/cli/epinio_app_env_list.md)
          - [epinio_app_env_set](references/cli/epinio_app_env_set.md)
          - [epinio_app_env_show](references/cli/epinio_app_env_show.md)
          - [epinio_app_env_unset](references/cli/epinio_app_env_unset.md)

        - [epinio_app_list](references/cli/epinio_app_list.md)
        - [epinio_app_logs](references/cli/epinio_app_logs.md)
        - [epinio_app_manifest](references/cli/epinio_app_manifest.md)
        - [epinio_app_show](references/cli/epinio_app_show.md)
        - [epinio_app_update](references/cli/epinio_app_update.md)

      - [epinio_config](references/cli/epinio_config.md)

        - [epinio_config_colors](references/cli/epinio_config_colors.md)
        - [epinio_config_show](references/cli/epinio_config_show.md)
        - [epinio_config_update](references/cli/epinio_config_update.md)

      - [epinio_info](references/cli/epinio_info.md)
      - [epinio_namespace](references/cli/epinio_namespace.md)

        - [epinio_namespace_create](references/cli/epinio_namespace_create.md)
        - [epinio_namespace_delete](references/cli/epinio_namespace_delete.md)
        - [epinio_namespace_list](references/cli/epinio_namespace_list.md)
        - [epinio_namespace_show](references/cli/epinio_namespace_show.md)

      - [epinio_push](references/cli/epinio_push.md)
      - [epinio_server](references/cli/epinio_server.md)
      - [epinio_service](references/cli/epinio_service.md)

        - [epinio_service_bind](references/cli/epinio_service_bind.md)
        - [epinio_service_create](references/cli/epinio_service_create.md)
        - [epinio_service_delete](references/cli/epinio_service_delete.md)
        - [epinio_service_list](references/cli/epinio_service_list.md)
        - [epinio_service_show](references/cli/epinio_service_show.md)
        - [epinio_service_unbind](references/cli/epinio_service_unbind.md)

      - [epinio_target](references/cli/epinio_target.md)
      - [epinio_version](references/cli/epinio_version.md)
  - [CLI Configuration](references/configuration.md)
  - [Supported Applications](references/supported-apps.md)
  - [Application Manifests](references/manifests.md)
  - [Services](references/services.md)
  - [API](references/api.md)
