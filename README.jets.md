## AWS Lambda Ruby Runtime Interface Client Fork

This fork for the Lambda Ruby RIC only exists until AWS releases an up-to-date version.

See: https://github.com/aws/aws-lambda-ruby-runtime-interface-client/issues/15#issuecomment-1737318563

## Version Strategy

This fork uses a separate version for its releases to clarify which version it is tracking.

* [fork version](/lib/aws_lambda_ric_jets/version.rb): This is the fork version of with the renamed gem aws_lambda_ric_jets published to RubyGems.
* [upstream official version]((/lib/aws_lambda_ric/version.rb)): This is not necessarily what's been released on RubyGems, but the version at the point the fork was made from master. Master has the important fixes already. It's the whole reason for this gem. AWS probably need to make some time to test and release the gem.
