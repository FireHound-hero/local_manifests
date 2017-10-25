Cherry pick listed commits in coresponding repos before building

git fetch https://review.lineageos.org/LineageOS/android_vendor_qcom_opensource_cryptfs_hw refs/changes/37/187837/3 && git cherry-pick FETCH_HEAD

git fetch https://review.lineageos.org/LineageOS/android_hardware_qcom_audio refs/changes/34/189434/1 && git cherry-pick FETCH_HEAD

git fetch https://review.lineageos.org/LineageOS/android_hardware_qcom_audio refs/changes/37/189437/1 && git cherry-pick FETCH_HEAD

git fetch https://review.lineageos.org/LineageOS/android_hardware_qcom_audio refs/changes/36/189436/1 && git cherry-pick FETCH_HEAD

git fetch https://review.lineageos.org/LineageOS/android_hardware_qcom_audio refs/changes/35/189435/1 && git cherry-pick FETCH_HEAD
