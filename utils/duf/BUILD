go build \
    -trimpath \
    -buildmode=pie \
    -mod=readonly \
    -modcacherw \
    -ldflags "-X main.Version=$VERSION -linkmode external -extldflags \"${LDFLAGS}\"" \
    -o "$pkgname" . &&

go clean -modcache &&

prepare_install &&

install -Dm755 "$MODULE" /usr/bin/
