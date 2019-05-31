FROM gcr.io/jenkinsxio/prow/tide-1:v20190411-88a8176fb
RUN rm -rf /app/prow/cmd/tide/app.binary.runfiles/io_k8s_test_infra/prow/cmd/tide/linux_amd64_pure_stripped/app.binary
RUN date > /app/prow/cmd/tide/app.binary.runfiles/io_k8s_test_infra/prow/cmd/tide/linux_amd64_pure_stripped/version
ADD app.binary  /app/prow/cmd/tide/app.binary.runfiles/io_k8s_test_infra/prow/cmd/tide/linux_amd64_pure_stripped/

