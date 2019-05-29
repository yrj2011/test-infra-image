FROM gcr.io/jenkinsxio/prow/hook-1:v20190411-88a8176fb
RUN rm -rf /app/prow/cmd/hook/app.binary.runfiles/io_k8s_test_infra/prow/cmd/hook/linux_amd64_pure_stripped/app.binary
RUN date > /app/prow/cmd/hook/app.binary.runfiles/io_k8s_test_infra/prow/cmd/hook/linux_amd64_pure_stripped/version
ADD app.binary  /app/prow/cmd/hook/app.binary.runfiles/io_k8s_test_infra/prow/cmd/hook/linux_amd64_pure_stripped/

