load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_go",
    urls = ["https://github.com/bazelbuild/rules_go/releases/download/0.18.3/rules_go-0.18.3.tar.gz"],
    sha256 = "86ae934bd4c43b99893fc64be9d9fc684b81461581df7ea8fc291c816f5ee8c5",
)

http_archive(
    name = "bazel_gazelle",
    urls = ["https://github.com/bazelbuild/bazel-gazelle/releases/download/0.17.0/bazel-gazelle-0.17.0.tar.gz"],
    sha256 = "3c681998538231a2d24d0c07ed5a7658cb72bfb5fd4bf9911157c0e9ac6a2687",
)

load("@io_bazel_rules_go//go:deps.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()

go_register_toolchains()

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

gazelle_dependencies()

go_repository(
    name = "com_github_armon_go_metrics",
    commit = "3df31a1ada83e310c2e24b267c8e8b68836547b4",
    importpath = "github.com/armon/go-metrics",
)

go_repository(
    name = "com_github_aws_aws_sdk_go",
    commit = "ca6d5f771b63df153f02fe5b117434d5ebafeeda",
    importpath = "github.com/aws/aws-sdk-go",
)

go_repository(
    name = "com_github_bgentry_go_netrc",
    commit = "9fd32a8b3d3d3f9d43c341bfe098430e07609480",
    importpath = "github.com/bgentry/go-netrc",
)

go_repository(
    name = "com_github_cheggaaa_pb",
    commit = "c112833d014c77e8bde723fd0158e3156951639f",
    importpath = "github.com/cheggaaa/pb",
)

go_repository(
    name = "com_github_golang_protobuf",
    commit = "b5d812f8a3706043e23a9cd5babf2e5423744d30",
    importpath = "github.com/golang/protobuf",
)

go_repository(
    name = "com_github_golang_snappy",
    commit = "2e65f85255dbc3072edf28d6b5b8efc472979f5a",
    importpath = "github.com/golang/snappy",
)

go_repository(
    name = "com_github_googleapis_gax_go",
    commit = "beaecbbdd8af86aa3acf14180d53828ce69400b2",
    importpath = "github.com/googleapis/gax-go",
)

go_repository(
    name = "com_github_hashicorp_consul",
    commit = "ea5210a30e154f4da9a4c8e729b45b8ce7b9b92c",
    importpath = "github.com/hashicorp/consul",
)

go_repository(
    name = "com_github_hashicorp_errwrap",
    commit = "7554cd9344cec97297fa6649b055a8c98c2a1e55",
    importpath = "github.com/hashicorp/errwrap",
)

go_repository(
    name = "com_github_hashicorp_go_checkpoint",
    commit = "bbe6c410aa4be4194cb490a2bde8c3c33f295541",
    importpath = "github.com/hashicorp/go-checkpoint",
)

go_repository(
    name = "com_github_hashicorp_go_cleanhttp",
    commit = "e8ab9daed8d1ddd2d3c4efba338fe2eeae2e4f18",
    importpath = "github.com/hashicorp/go-cleanhttp",
)

go_repository(
    name = "com_github_hashicorp_go_getter",
    commit = "e1437d0bbb37a1fa61cdb924b034352c823cb89b",
    importpath = "github.com/hashicorp/go-getter",
)

go_repository(
    name = "com_github_hashicorp_go_multierror",
    commit = "ed905158d87462226a13fe39ddf685ea65f1c11f",
    importpath = "github.com/hashicorp/go-multierror",
)

go_repository(
    name = "com_github_hashicorp_go_retryablehttp",
    commit = "73489d0a1476f0c9e6fb03f9c39241523a496dfd",
    importpath = "github.com/hashicorp/go-retryablehttp",
)

go_repository(
    name = "com_github_hashicorp_go_rootcerts",
    commit = "6bb64b370b90e7ef1fa532be9e591a81c3493e00",
    importpath = "github.com/hashicorp/go-rootcerts",
)

go_repository(
    name = "com_github_hashicorp_go_safetemp",
    commit = "c9a55de4fe06c920a71964b53cfe3dd293a3c743",
    importpath = "github.com/hashicorp/go-safetemp",
)

go_repository(
    name = "com_github_hashicorp_go_sockaddr",
    commit = "6d291a969b86c4b633730bfc6b8b9d64c3aafed9",
    importpath = "github.com/hashicorp/go-sockaddr",
)

go_repository(
    name = "com_github_hashicorp_go_uuid",
    commit = "4f571afc59f3043a65f8fe6bf46d887b10a01d43",
    importpath = "github.com/hashicorp/go-uuid",
)

go_repository(
    name = "com_github_hashicorp_go_version",
    commit = "03c5bf6be031b6dd45afec16b1cf94fc8938bc77",
    importpath = "github.com/hashicorp/go-version",
)

go_repository(
    name = "com_github_hashicorp_golang_lru",
    commit = "7087cb70de9f7a8bc0a10c375cb0d2280a8edf9c",
    importpath = "github.com/hashicorp/golang-lru",
)

go_repository(
    name = "com_github_hashicorp_hcl",
    commit = "65a6292f0157eff210d03ed1bf6c59b190b8b906",
    importpath = "github.com/hashicorp/hcl",
)

go_repository(
    name = "com_github_hashicorp_packer",
    commit = "54d2b32d8c96aeefd6cdc59f4064ef68143fc035",
    importpath = "github.com/hashicorp/packer",
)

go_repository(
    name = "com_github_hashicorp_serf",
    commit = "65da6f27f6e551e03d99364ecc0607e91e526b00",
    importpath = "github.com/hashicorp/serf",
)

go_repository(
    name = "com_github_hashicorp_vault",
    commit = "0082501623c0b704b87b1fbc84c2d725994bac54",
    importpath = "github.com/hashicorp/vault",
)

go_repository(
    name = "com_github_hashicorp_yamux",
    commit = "d1caa6c97c9fc1cc9e83bbe34d0603f9ff0ce8bd",
    importpath = "github.com/hashicorp/yamux",
)

go_repository(
    name = "com_github_jmespath_go_jmespath",
    commit = "c2b33e84",
    importpath = "github.com/jmespath/go-jmespath",
)

go_repository(
    name = "com_github_mattn_go_colorable",
    commit = "167de6bfdfba052fa6b2d3664c8f5272e23c9072",
    importpath = "github.com/mattn/go-colorable",
)

go_repository(
    name = "com_github_mattn_go_isatty",
    commit = "c2a7a6ca930a4cd0bc33a3f298eb71960732a3a7",
    importpath = "github.com/mattn/go-isatty",
)

go_repository(
    name = "com_github_mitchellh_go_homedir",
    commit = "af06845cf3004701891bf4fdb884bfe4920b3727",
    importpath = "github.com/mitchellh/go-homedir",
)

go_repository(
    name = "com_github_mitchellh_go_testing_interface",
    commit = "6d0b8010fcc857872e42fc6c931227569016843c",
    importpath = "github.com/mitchellh/go-testing-interface",
)

go_repository(
    name = "com_github_mitchellh_iochan",
    commit = "87b45ffd0e9581375c491fef3d32130bb15c5bd7",
    importpath = "github.com/mitchellh/iochan",
)

go_repository(
    name = "com_github_mitchellh_mapstructure",
    commit = "db1efb556f84b25a0a13a04aad883943538ad2e0",
    importpath = "github.com/mitchellh/mapstructure",
)

go_repository(
    name = "com_github_mitchellh_packer",
    commit = "9de8545875a287582114546fe12d29401a886733",
    importpath = "github.com/mitchellh/packer",
)

go_repository(
    name = "com_github_mitchellh_reflectwalk",
    commit = "417edcfd99a4d472c262e58f22b4bfe97580f03e",
    importpath = "github.com/mitchellh/reflectwalk",
)

go_repository(
    name = "com_github_pierrec_lz4",
    commit = "635575b42742856941dbc767b44905bb9ba083f6",
    importpath = "github.com/pierrec/lz4",
)

go_repository(
    name = "com_github_rwtodd_go_sed",
    commit = "906bc69c939459588697920a2bef44a11437693b",
    importpath = "github.com/rwtodd/Go.Sed",
)

go_repository(
    name = "com_github_ryanuber_go_glob",
    commit = "256dc444b735e061061cf46c809487313d5b0065",
    importpath = "github.com/ryanuber/go-glob",
)

go_repository(
    name = "com_github_ugorji_go",
    commit = "c88ee250d0221a57af388746f5cf03768c21d6e2",
    importpath = "github.com/ugorji/go",
)

go_repository(
    name = "com_github_ulikunitz_xz",
    commit = "6f934d456d51e742b4eeab20d925a827ef22320a",
    importpath = "github.com/ulikunitz/xz",
)

go_repository(
    name = "com_github_vmware_govmomi",
    commit = "6103db21b38cbdfda3100fed08b988fc2d83aa1a",
    importpath = "github.com/vmware/govmomi",
)

go_repository(
    name = "com_google_cloud_go",
    commit = "fcb9a2d5f791d07be64506ab54434de65989d370",
    importpath = "cloud.google.com/go",
)

go_repository(
    name = "in_gopkg_cheggaaa_pb_v2",
    commit = "c112833d014c77e8bde723fd0158e3156951639f",
    importpath = "gopkg.in/cheggaaa/pb.v2",
)

go_repository(
    name = "in_gopkg_fatih_color_v1",
    commit = "5b77d2a35fb0ede96d138fc9a99f5c9b6aef11b4",
    importpath = "gopkg.in/fatih/color.v1",
)

go_repository(
    name = "in_gopkg_mattn_go_colorable_v0",
    commit = "167de6bfdfba052fa6b2d3664c8f5272e23c9072",
    importpath = "gopkg.in/mattn/go-colorable.v0",
)

go_repository(
    name = "in_gopkg_mattn_go_isatty_v0",
    commit = "c2a7a6ca930a4cd0bc33a3f298eb71960732a3a7",
    importpath = "gopkg.in/mattn/go-isatty.v0",
)

go_repository(
    name = "in_gopkg_mattn_go_runewidth_v0",
    commit = "3ee7d812e62a0804a7d0a324e0249ca2db3476d3",
    importpath = "gopkg.in/mattn/go-runewidth.v0",
)

go_repository(
    name = "in_gopkg_vividcortex_ewma_v1",
    commit = "b24eb346a94c3ba12c1da1e564dbac1b498a77ce",
    importpath = "gopkg.in/VividCortex/ewma.v1",
)

go_repository(
    name = "io_opencensus_go",
    commit = "75c0cca22312e51bfd4fafdbe9197ae399e18b38",
    importpath = "go.opencensus.io",
)

go_repository(
    name = "org_golang_google_api",
    commit = "0cbcb99a9ea0c8023c794b2693cbe1def82ed4d7",
    importpath = "google.golang.org/api",
)

go_repository(
    name = "org_golang_google_appengine",
    commit = "54a98f90d1c46b7731eb8fb305d2a321c30ef610",
    importpath = "google.golang.org/appengine",
)

go_repository(
    name = "org_golang_google_genproto",
    commit = "e7d98fc518a78c9f8b5ee77be7b0b317475d89e1",
    importpath = "google.golang.org/genproto",
)

go_repository(
    name = "org_golang_google_grpc",
    commit = "25c4f928eaa6d96443009bd842389fb4fa48664e",
    importpath = "google.golang.org/grpc",
)

go_repository(
    name = "org_golang_x_net",
    commit = "1f3472d942ba824034fb77cab6a6cfc1bc8a2c3c",
    importpath = "golang.org/x/net",
)

go_repository(
    name = "org_golang_x_oauth2",
    commit = "9f3314589c9a9136388751d9adae6b0ed400978a",
    importpath = "golang.org/x/oauth2",
)

go_repository(
    name = "org_golang_x_sync",
    commit = "56d357773e8497dfd526f0727e187720d1093757",
    importpath = "golang.org/x/sync",
)

go_repository(
    name = "org_golang_x_sys",
    commit = "e8e3143a4f4a00f1fafef0dd82ba78223281b01b",
    importpath = "golang.org/x/sys",
)

go_repository(
    name = "org_golang_x_text",
    commit = "f21a4dfb5e38f5895301dc265a8def02365cc3d0",
    importpath = "golang.org/x/text",
)

go_repository(
    name = "org_golang_x_time",
    commit = "fbb02b2291d28baffd63558aa44b4b56f178d650",
    importpath = "golang.org/x/time",
)
