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
             <oi>https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/vpc.yml</li>
            </ol>
        </td>
        <td nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/vpc.yml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                    </td>
                </tr>
            </table>
            <table>
                <tr>
                    <th align="left">View in Designer</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/designer/home?region=us-west-2&templateURL=https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/vpc.json" target="_blank"><img src="https://s3.amazonaws.com/stelligent-public/media/cloudformation-diagrams/vpc-200x200.jpg" width:100% alt="View in Designer"></a>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>
