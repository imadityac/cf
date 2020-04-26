<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/stelligent/cloudformation_templates/blob/master/infrastructure/vpc.yml">VPC (Virtual Private Cloud)</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
           <p>Creates an entire VPC from scratch for Lab or Permanent.</p>
           <h6>Create Details</h6>
           <ol>
            <li>Single VPC</li>
            <li>2 Public Subnets</li>
            <li>2 Private Subnets</li>
            <li>Public Route Table</li>
            <li>Private Route Table</li>
            <li>Internet Gateway</li>
            <ul>
              <li>Attached to the Public Route Table</li>
            </ul>
            <li>VPC Endpoint</li>
            <li>Instance Access Security Group</li>
            <ul>
              <li>Instance to Instance Access</li>
            </ul>
            <li>Remote Access Security Group</li>
            <ul>
              <li>This can be used for to allow site-to-site VPN or Direct Connect Networks access to instances.</li>
            </ul>
           </ol>
            <h6>Public S3 URL</h6>
            <ol>
             <oi>https://cf-templates-1lev62qykeen-us-east-1.s3.amazonaws.com/2020117SYK-new.templateqb2p3vhbbv.json</li>
            </ol>
        </td>
        <td nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                     <td>
                        <a href="
                    https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/quickcreate?templateUrl=https%3A%2F%2Fs3-external-1.amazonaws.com%2Fcf-templates-1lev62qykeen-us-east-1%2F2020117SYK-new.templateqb2p3vhbbv&stackName=aaaa&param_AllowAllInboundPrivateRuleNumber=150&param_AllowAllOutboundPrivateRuleNumber=100&param_AllowAllOutboundPublicRuleNumber=100&param_AllowHttpToPublicRuleNumber=200&param_AllowHttpsToPublicRuleNumber=205&param_AllowRemoteNetworkPublicRuleNumber=105&param_AllowReturnTrafficToPublicRuleNumber=900&param_AllowVpcSubnetsRuleNumber=100&param_AvailabilityZone1=a&param_AvailabilityZone2=b&param_DeleteAfter=00%2F00%2F201x&param_Deny8080ToPublicRuleNumber=830&param_Deny8443ToPublicRuleNumber=835&param_DenyAuroraToPublicRuleNumber=810&param_DenyMysqlToPublicRuleNumber=800&param_DenyNFSToPublicRuleNumber=815&param_DenyOracleToPublicRuleNumber=805&param_DenyPostgreToPublicRuleNumber=825&param_DenyRDPToPublicRuleNumber=820&param_Owner=FirstName%20LastName&param_PrivateSubnetCidrBlock1=10.0.4.0%2F24&param_PrivateSubnetCidrBlock2=10.0.5.0%2F24&param_Project=MySQL%20RDS%20Creation&param_PublicSubnetCidrBlock1=10.0.1.0%2F24&param_PublicSubnetCidrBlock2=10.0.2.0%2F24&param_SSHLocation=0.0.0.0%2F0&param_VPCSubnetCidrBlock=10.0.0.0%2F16" target="_blank"><img src="https://s3.amazonaws.com/stelligent-public/media/cloudformation-diagrams/vpc-200x200.jpg" width:100% alt="View in Designer"></a>
                    </td>
                </tr>
            </table>
            <table>
                <tr>
                    <th align="left">View in Designer</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/designer/home?region=us-west-2&templateURL=https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/vpc.json" target="_blank"><img src="" width:100% alt="View in Designer"></a>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>
