package(default_visibility = ["PUBLIC"])

go_get(
    name = "context",
    get = "golang.org/x/net/context",
)

go_get(
    name = "protobuf",
    get = "github.com/golang/protobuf/...",
)

go_get(
    name = "protoc-gen-go",
    binary = True,
    get = [],
    install = ["github.com/golang/protobuf/protoc-gen-go"],
    deps = [":protobuf"],
)

go_get(
    name = "annotations",
    get = "google.golang.org/genproto/googleapis/api/annotations",
    deps = [":protobuf"],
)

