# ios-bootstrap

Codemagic workflow (`newapp-ios`) that builds and signs new.live users' iOS
apps and delivers them to the user's TestFlight. Nothing app-specific lives
here: the platform triggers builds through the Codemagic API and injects the
scaffold URL and the user's App Store Connect key per build.

Source of truth: `backend/engine/mobile_ci/codemagic.yaml` in the platform
repo — re-run `mobile_ci/bootstrap_codemagic.sh` (BOOTSTRAP_REPO=neverendingworld/ios-bootstrap)
to update this copy.
