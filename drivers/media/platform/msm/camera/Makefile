obj-$(CONFIG_SPECTRA_CAMERA) += cam_req_mgr/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_utils/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_core/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_sync/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_smmu/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_cpas/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_cdm/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_isp/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_sensor_module/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_icp/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_jpeg/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_fd/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_lrme/

# find cam* -name Makefile -exec sed -i -e '/-Idrivers/d' {} +
# find cam* -name Makefile -exec sed -i -e '/./,$!d' {} +
# find drivers/media/platform/msm/camera -name '*.h' -exec dirname {} \; | sort | uniq | while read line; do echo '    -I'${line}' \'; done
subdir-ccflags-y := \
    -Idrivers/media/platform/msm/camera/cam_cdm \
    -Idrivers/media/platform/msm/camera/cam_core \
    -Idrivers/media/platform/msm/camera/cam_cpas \
    -Idrivers/media/platform/msm/camera/cam_cpas/cpas_top \
    -Idrivers/media/platform/msm/camera/cam_cpas/include \
    -Idrivers/media/platform/msm/camera/cam_fd \
    -Idrivers/media/platform/msm/camera/cam_fd/fd_hw_mgr \
    -Idrivers/media/platform/msm/camera/cam_fd/fd_hw_mgr/fd_hw \
    -Idrivers/media/platform/msm/camera/cam_icp \
    -Idrivers/media/platform/msm/camera/cam_icp/fw_inc \
    -Idrivers/media/platform/msm/camera/cam_icp/icp_hw/a5_hw \
    -Idrivers/media/platform/msm/camera/cam_icp/icp_hw/bps_hw \
    -Idrivers/media/platform/msm/camera/cam_icp/icp_hw/icp_hw_mgr \
    -Idrivers/media/platform/msm/camera/cam_icp/icp_hw/icp_hw_mgr/include \
    -Idrivers/media/platform/msm/camera/cam_icp/icp_hw/include \
    -Idrivers/media/platform/msm/camera/cam_icp/icp_hw/ipe_hw \
    -Idrivers/media/platform/msm/camera/cam_isp \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/hw_utils/include \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/hw_utils/irq_controller \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/include \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/ife_csid_hw \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/include \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/vfe_hw \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/vfe_hw/vfe170 \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/vfe_hw/vfe_bus \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/vfe_hw/vfe_bus/include \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/vfe_hw/vfe_top \
    -Idrivers/media/platform/msm/camera/cam_isp/isp_hw_mgr/isp_hw/vfe_hw/vfe_top/include \
    -Idrivers/media/platform/msm/camera/cam_jpeg \
    -Idrivers/media/platform/msm/camera/cam_jpeg/jpeg_hw \
    -Idrivers/media/platform/msm/camera/cam_jpeg/jpeg_hw/include \
    -Idrivers/media/platform/msm/camera/cam_jpeg/jpeg_hw/jpeg_dma_hw \
    -Idrivers/media/platform/msm/camera/cam_jpeg/jpeg_hw/jpeg_enc_hw \
    -Idrivers/media/platform/msm/camera/cam_lrme \
    -Idrivers/media/platform/msm/camera/cam_lrme/lrme_hw_mgr \
    -Idrivers/media/platform/msm/camera/cam_lrme/lrme_hw_mgr/lrme_hw \
    -Idrivers/media/platform/msm/camera/cam_req_mgr \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/3dsl_eeprom \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_actuator \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_cci \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_csiphy \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_csiphy/include \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_eeprom \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_flash \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_ir_led \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_ois \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_res_mgr \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_sensor \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_sensor_io \
    -Idrivers/media/platform/msm/camera/cam_sensor_module/cam_sensor_utils \
    -Idrivers/media/platform/msm/camera/cam_smmu \
    -Idrivers/media/platform/msm/camera/cam_sync \
    -Idrivers/media/platform/msm/camera/cam_utils
