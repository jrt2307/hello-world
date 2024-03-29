<?xml version='1.0' encoding='UTF-8'?>
<!DOCTYPE UIConfig PUBLIC "sailpoint.dtd" "sailpoint.dtd">
<UIConfig created="1566242490174" id="ff8080816cab53a8016cab53c73e00bd" modified="1566610318478" name="UIConfig">
  <Attributes>
    <Map>
      <entry key="accountGroupIdentityTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="identity-name" headerKey="name" hideable="true" property="identity.name" sortProperty="identity.name" sortable="true" stateId="identity-name"/>
            <ColumnConfig dataIndex="identity-firstname" headerKey="firstName" hideable="true" property="identity.firstname" sortProperty="identity.firstname" sortable="true" stateId="identity-firstname"/>
            <ColumnConfig dataIndex="identity-lastname" headerKey="lastName" hideable="true" property="identity.lastname" sortProperty="identity.lastname" sortable="true" stateId="identity-lastname"/>
          </List>
        </value>
      </entry>
      <entry key="accountGroupMembershipExclusions">
        <value>
          <List>
            <ColumnConfig dataIndex="parent-accountGroup" headerKey="cert_exclusions_col_account_grp" hideable="true" property="parent.accountGroup" sortProperty="parent.accountGroup" sortable="true" stateId="parent-accountGroup"/>
            <ColumnConfig dataIndex="targetDisplayName" headerKey="cert_exclusions_col_account" hideable="true" property="targetDisplayName" sortProperty="targetDisplayName" sortable="true" stateId="targetDisplayName"/>
            <ColumnConfig dataIndex="type" headerKey="cert_exclusions_col_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="SPT_description" headerKey="cert_exclusions_col_desc" hideable="true" renderer="SailPoint.certification.ExclusionsGrid.renderDescription" sortProperty="SPT_description" sortable="true" stateId="SPT_description"/>
            <ColumnConfig dataIndex="parent-explanation" headerKey="cert_exclusions_col_reason" hideable="true" property="parent.explanation" sortProperty="parent.explanation" stateId="parent-explanation"/>
          </List>
        </value>
      </entry>
      <entry key="accountGroupPermissionTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="target" headerKey="target" hideable="true" property="target" renderer="renderTarget" sortProperty="target" sortable="true" stateId="target"/>
            <ColumnConfig dataIndex="rights" headerKey="rights" hideable="true" property="rights" sortProperty="rights" sortable="true" stateId="rights"/>
            <ColumnConfig dataIndex="annotation" headerKey="annotation" hideable="true" property="annotation" sortProperty="annotation" sortable="true" stateId="annotation"/>
          </List>
        </value>
      </entry>
      <entry key="accountGroupPermissionsExclusions">
        <value>
          <List>
            <ColumnConfig dataIndex="parent-accountGroup" headerKey="cert_exclusions_col_account_grp" hideable="true" property="parent.accountGroup" sortProperty="parent.accountGroup" sortable="true" stateId="parent-accountGroup"/>
            <ColumnConfig dataIndex="type" headerKey="cert_exclusions_col_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="SPT_description" headerKey="cert_exclusions_col_desc" hideable="true" renderer="SailPoint.certification.ExclusionsGrid.renderDescription" sortProperty="SPT_description" sortable="true" stateId="SPT_description"/>
            <ColumnConfig dataIndex="parent-explanation" headerKey="cert_exclusions_col_reason" hideable="true" property="parent.explanation" sortProperty="parent.explanation" stateId="parent-explanation"/>
          </List>
        </value>
      </entry>
      <entry key="accountGroupTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="displayableName" headerKey="name" hideable="true" property="displayableName" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="application" headerKey="application" hideable="true" property="application.name" sortProperty="application.name" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="attribute" headerKey="attribute" hideable="true" property="attribute" sortProperty="attribute" sortable="true" stateId="attribute"/>
            <ColumnConfig dataIndex="value" headerKey="native_identity" hideable="true" property="value" sortProperty="value" sortable="true" stateId="value"/>
            <ColumnConfig dataIndex="owner" headerKey="owner" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner"/>
          </List>
        </value>
      </entry>
      <entry key="accountIconConfig">
        <value>
          <List>
            <AccountIconConfig attribute="privileged" source="/images/icons/icon_Star.png" title="This is a privileged account" value="true"/>
            <AccountIconConfig attribute="service" source="/images/icons/modeler_profile_16.png" title="This is a service account" value="true"/>
            <AccountIconConfig attribute="inactive" source="/images/icons/certif_approved_16.png" title="Account Enabled" value="false"/>
            <AccountIconConfig attribute="inactive" source="/images/icons/certif_rejected_16.png" title="Account Disabled" value="true"/>
          </List>
        </value>
      </entry>
      <entry key="applicationAccountsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="nativeIdentity" headerKey="app_accts_grid_native_identity" hideable="true" property="nativeIdentity" sortProperty="nativeIdentity" sortable="true" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="displayName" headerKey="app_accts_grid_account_name" hideable="true" property="displayName" renderer="SailPoint.grid.Util.renderAccountWithIcons" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="instance" headerKey="app_accts_grid_instance" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="IIQ_status" headerKey="app_accts_grid_status" hideable="true" renderer="SailPoint.grid.Util.renderStatusWithIcon" stateId="IIQ_status"/>
            <ColumnConfig dataIndex="lastRefresh" headerKey="app_accts_grid_last_refresh" hideable="true" property="lastRefresh" sortProperty="lastRefresh" sortable="true" stateId="lastRefresh"/>
            <ColumnConfig dataIndex="identity-displayName" headerKey="app_accts_grid_identity_display_name" hideable="true" property="identity.displayName" renderer="SailPoint.Define.Applications.AccountsGrid.renderIdentityNavLink" sortProperty="identity.displayName" sortable="true" stateId="identity-displayName"/>
            <ColumnConfig dataIndex="identity-name" headerKey="app_accts_grid_identity_name" hidden="true" hideable="true" property="identity.name" sortProperty="identity.name" sortable="true" stateId="identity-name"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="identity-id" fieldOnly="true" property="identity.id" sortProperty="identity.id" stateId="identity-id"/>
            <ColumnConfig dataIndex="IIQ_accountIcons" fieldOnly="true" stateId="IIQ_accountIcons"/>
            <ColumnConfig dataIndex="IIQ_status_class" fieldOnly="true" stateId="IIQ_status_class"/>
          </List>
        </value>
      </entry>
      <entry key="applicationTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="host" headerKey="host" hideable="true" property="host" sortProperty="host" stateId="host"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="modified" headerKey="modified" hideable="true" property="modified" renderer="SailPoint.Date.DateTimeRenderer" sortProperty="modified" sortable="true" stateId="modified"/>
          </List>
        </value>
      </entry>
      <entry key="batchRequestItemsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="requestData" headerKey="batch_details_grid_request_data" hideable="true" property="requestData" sortProperty="requestData" sortable="true" stateId="requestData"/>
            <ColumnConfig dataIndex="result" headerKey="batch_details_grid_result" hideable="true" property="result" sortProperty="result" sortable="true" stateId="result"/>
            <ColumnConfig dataIndex="status" headerKey="batch_details_grid_status" hideable="true" property="status" sortProperty="status" sortable="true" stateId="status"/>
            <ColumnConfig dataIndex="identityRequestId" headerKey="batch_details_grid_identity_request_id" hideable="true" property="identityRequestId" sortProperty="identityRequestId" sortable="true" stateId="identityRequestId"/>
            <ColumnConfig dataIndex="errorMessage" fieldOnly="true" property="errorMessage" sortProperty="errorMessage" stateId="errorMessage"/>
          </List>
        </value>
      </entry>
      <entry key="batchRequestTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="fileName" headerKey="fileName" hideable="true" property="fileName" sortProperty="fileName" sortable="true" stateId="fileName"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="requestedDate" hideable="true" property="created" sortProperty="created" sortable="true" stateId="created" timeStyle="short"/>
            <ColumnConfig dataIndex="runDate" dateStyle="short" headerKey="runDate" hideable="true" property="runDate" sortProperty="runDate" sortable="true" stateId="runDate" timeStyle="short"/>
            <ColumnConfig dataIndex="completedDate" dateStyle="short" headerKey="completedDate" hideable="true" property="completedDate" sortProperty="completedDate" sortable="true" stateId="completedDate" timeStyle="short"/>
            <ColumnConfig dataIndex="recordCount" headerKey="recordCount" hideable="true" property="recordCount" sortProperty="recordCount" sortable="true" stateId="recordCount"/>
            <ColumnConfig dataIndex="status" headerKey="status" hideable="true" property="status" sortProperty="status" sortable="true" stateId="status"/>
            <ColumnConfig dataIndex="errorMessage" fieldOnly="true" property="errorMessage" sortProperty="errorMessage" stateId="errorMessage"/>
          </List>
        </value>
      </entry>
      <entry key="bulkCustomEntityFieldsInclude"/>
      <entry key="businessRoleMembershipCertificationItemTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="decision" headerKey="decision" property="IIQ_calculatedStatus" renderer="SailPoint.certification.WorksheetGrid.renderButtons" sortProperty="IIQ_calculatedStatus" stateId="decision"/>
            <ColumnConfig dataIndex="parent-identity" headerKey="cert_item_tbl_header_identity" hideable="true" property="parent.identity" sortProperty="parent.identity" sortable="true" stateId="parent-identity"/>
            <ColumnConfig dataIndex="parent-firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="parent.firstname" sortProperty="parent.firstname" sortable="true" stateId="parent-firstname"/>
            <ColumnConfig dataIndex="parent-lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="parent.lastname" sortProperty="parent.lastname" sortable="true" stateId="parent-lastname"/>
            <ColumnConfig dataIndex="IIQ_description" headerKey="cert_item_tbl_header_description" hideable="true" percentWidth="40" property="IIQ_description" renderer="SailPoint.certification.WorksheetGrid.renderDescription" sortProperty="IIQ_description" sortable="true" stateId="IIQ_description"/>
            <ColumnConfig dataIndex="IIQ_entitlementDescription" fieldOnly="true" headerKey="cert_item_tbl_header_full_description" hidden="true" property="IIQ_entitlementDescription" renderer="SailPoint.certification.WorksheetGrid.emptyRenderer" sortProperty="IIQ_entitlementDescription" stateId="IIQ_entitlementDescription"/>
            <ColumnConfig dataIndex="exceptionApplication" headerKey="cert_item_tbl_header_application" hideable="true" property="exceptionApplication" renderer="SailPoint.certification.WorksheetGrid.renderApplication" sortProperty="exceptionApplication" stateId="exceptionApplication"/>
            <ColumnConfig dataIndex="exceptionEntitlements-displayName" headerKey="cert_item_tbl_header_accountDisplayName" hideable="true" property="exceptionEntitlements.displayName" sortProperty="exceptionEntitlements.displayName" stateId="exceptionEntitlements-displayName"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.WorksheetGrid.renderCommentStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="parent-compositeScore" headerKey="cert_item_tbl_header_compositescore" hideable="true" property="parent.compositeScore" sortProperty="parent.compositeScore" sortable="true" stateId="parent-compositeScore"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
          </List>
        </value>
      </entry>
      <entry key="businessRoleMembershipContinuousCertificationItemTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="decision" headerKey="decision" property="IIQ_calculatedStatus" renderer="SailPoint.certification.WorksheetGrid.renderButtons" sortProperty="IIQ_calculatedStatus" stateId="decision"/>
            <ColumnConfig dataIndex="parent-identity" headerKey="cert_item_tbl_header_identity" hideable="true" property="parent.identity" sortProperty="parent.identity" sortable="true" stateId="parent-identity"/>
            <ColumnConfig dataIndex="parent-firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="parent.firstname" sortProperty="parent.firstname" sortable="true" stateId="parent-firstname"/>
            <ColumnConfig dataIndex="parent-lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="parent.lastname" sortProperty="parent.lastname" sortable="true" stateId="parent-lastname"/>
            <ColumnConfig dataIndex="IIQ_description" headerKey="cert_item_tbl_header_description" hideable="true" percentWidth="40" property="IIQ_description" renderer="SailPoint.certification.WorksheetGrid.renderDescription" sortProperty="IIQ_description" sortable="true" stateId="IIQ_description"/>
            <ColumnConfig dataIndex="IIQ_entitlementDescription" fieldOnly="true" headerKey="cert_item_tbl_header_full_description" hidden="true" property="IIQ_entitlementDescription" sortProperty="IIQ_entitlementDescription" stateId="IIQ_entitlementDescription"/>
            <ColumnConfig dataIndex="overdueDate" headerKey="cert_item_tbl_header_overdue" hideable="true" property="overdueDate" renderer="renderCertContinuousStateColumn" sortProperty="overdueDate" sortable="true" stateId="overdueDate"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.WorksheetGrid.renderCommentStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="parent-compositeScore" headerKey="cert_item_tbl_header_compositescore" hideable="true" property="parent.compositeScore" sortProperty="parent.compositeScore" sortable="true" stateId="parent-compositeScore"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="IIQ_continuousStateName" fieldOnly="true" property="IIQ_continuousStateName" sortProperty="IIQ_continuousStateName" stateId="IIQ_continuousStateName"/>
          </List>
        </value>
      </entry>
      <entry key="businessRoleRemediationItemTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="remediationIdentity" headerKey="label_biz_role_name" hideable="true" percentWidth="30" property="remediationIdentity" sortProperty="remediationIdentity" sortable="true" stateId="remediationIdentity"/>
            <ColumnConfig dataIndex="completionDate" dateStyle="short" headerKey="cert_stat_completed" hideable="true" percentWidth="20" property="completionDate" sortProperty="completionDate" sortable="true" stateId="completionDate" timeStyle="short"/>
            <ColumnConfig dataIndex="entitlements" headerKey="label_reqested_action" hideable="true" percentWidth="50" property="remediationDetails" sortProperty="remediationDetails" stateId="entitlements"/>
          </List>
        </value>
      </entry>
      <entry key="certificationAccessReviewsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="description" flex="1.0" headerKey="cert_grp_reviews_col_desc" hideable="true" property="description" sortProperty="name" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="completionStatus" headerKey="cert_grp_reviews_col_perc_complete" hideable="true" property="completionStatus" sortProperty="statistics.itemPercentComplete" sortable="true" stateId="completionStatus"/>
            <ColumnConfig dataIndex="phase" headerKey="cert_grp_reviews_col_phase" hideable="true" property="phase" sortProperty="phase" sortable="true" stateId="phase"/>
            <ColumnConfig dataIndex="phaseEnd" headerKey="cert_grp_reviews_col_phase_end" hideable="true" property="phaseEnd" sortProperty="phaseEnd" stateId="phaseEnd"/>
            <ColumnConfig dataIndex="tags" headerKey="cert_grp_reviews_col_tags" hideable="true" property="tags" sortProperty="tags" stateId="tags"/>
            <ColumnConfig dataIndex="certifiers" headerKey="cert_grp_reviews_col_certifiers" hideable="true" property="certifiers" sortProperty="certifiers" stateId="certifiers"/>
            <ColumnConfig dataIndex="due" headerKey="cert_grp_reviews_col_due" hideable="true" property="due" sortProperty="expiration" sortable="true" stateId="due"/>
            <ColumnConfig dataIndex="signed" headerKey="cert_grp_reviews_col_signed" hideable="true" property="signed" renderer="SailPoint.Date.DateTimeRenderer" sortProperty="signed" sortable="true" stateId="signed"/>
            <ColumnConfig dataIndex="electronicallySigned" headerKey="cert_grp_reviews_col_electronically_signed" hidden="true" hideable="true" property="electronicallySigned" renderer="SailPoint.grid.Util.renderBoolean" sortProperty="electronicallySigned" sortable="true" stateId="electronicallySigned"/>
            <ColumnConfig dataIndex="limitReassignments" fieldOnly="true" stateId="limitReassignments"/>
            <ColumnConfig dataIndex="isStaged" fieldOnly="true" stateId="isStaged"/>
          </List>
        </value>
      </entry>
      <entry key="certificationAccountGroupTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="accountGroup" headerKey="account_group" hideable="true" property="accountGroup" sortProperty="accountGroup" sortable="true" stateId="accountGroup"/>
            <ColumnConfig dataIndex="schemaObjectType" headerKey="type" hideable="true" property="schemaObjectType" sortProperty="schemaObjectType" sortable="true" stateId="schemaObjectType"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.BaseCertificationGrid.renderStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="IIQ_accountGroupDesc" headerKey="cert_entity_grid_hdr_acct_grp_desc" hideable="true" property="IIQ_accountGroupDesc" renderer="SailPoint.certification.BaseCertificationGrid.renderDescription" sortProperty="IIQ_accountGroupDesc" stateId="IIQ_accountGroupDesc"/>
            <ColumnConfig dataIndex="IIQ_hasDelegations" fieldOnly="true" property="IIQ_hasDelegations" sortProperty="IIQ_hasDelegations" stateId="IIQ_hasDelegations"/>
          </List>
        </value>
      </entry>
      <entry key="certificationBusinessRoleCompositionTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="targetDisplayName" headerKey="biz_role" hideable="true" property="targetDisplayName" sortProperty="targetDisplayName" sortable="true" stateId="targetDisplayName"/>
            <ColumnConfig dataIndex="IIQ_roleType" headerKey="cert_entity_tbl_header_role_type" hideable="true" property="IIQ_roleType" sortProperty="IIQ_roleType" stateId="IIQ_roleType"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.BaseCertificationGrid.renderStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="IIQ_hasDelegations" fieldOnly="true" property="IIQ_hasDelegations" sortProperty="IIQ_hasDelegations" stateId="IIQ_hasDelegations"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailAccountGroupMembershipsColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="exceptionEntitlements-nativeIdentity" fieldOnly="true" property="exceptionEntitlements.nativeIdentity" sortProperty="exceptionEntitlements.nativeIdentity" stateId="exceptionEntitlements-nativeIdentity"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="exceptionEntitlements-displayName" headerKey="account_name" property="exceptionEntitlements.displayName" renderer="SailPoint.certification.BaseCertificationGrid.renderGenericAccount" sortProperty="exceptionEntitlements.displayName" stateId="exceptionEntitlements-displayName"/>
            <ColumnConfig dataIndex="IIQ_identity" evaluator="sailpoint.web.view.certification.AccountGroupMembershipIdentityColumn" headerKey="identity" property="IIQ_identity" renderer="SailPoint.certification.BaseCertificationGrid.renderIdentity" sortProperty="IIQ_identity" stateId="IIQ_identity"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailAccountGroupPermissionsAppGranularityColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" evaluator="sailpoint.web.view.certification.ExceptionEntitlementsColumn" fieldOnly="true" property="IIQ_exceptionEntitlements" sortProperty="IIQ_exceptionEntitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="attribute" property="IIQ_attribute" renderer="SailPoint.certification.BaseCertificationGrid.renderAccountAttribute" sortProperty="IIQ_attribute" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="entitlements" property="IIQ_entitlements" renderer="SailPoint.certification.BaseCertificationGrid.renderAppGranularityEntitlement" sortProperty="IIQ_entitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailAccountGroupPermissionsColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" evaluator="sailpoint.web.view.certification.ExceptionEntitlementsColumn" fieldOnly="true" property="IIQ_exceptionEntitlements" sortProperty="IIQ_exceptionEntitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="attribute" property="IIQ_attribute" renderer="SailPoint.certification.BaseCertificationGrid.renderAccountAttribute" sortProperty="IIQ_attribute" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="entitlements" property="IIQ_entitlements" renderer="SailPoint.certification.BaseCertificationGrid.renderEntitlement" sortProperty="IIQ_entitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailAppGranularityEntitlementsColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="parent-targetName" fieldOnly="true" property="parent.targetName" sortProperty="parent.targetName" stateId="parent-targetName"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" evaluator="sailpoint.web.view.certification.ExceptionEntitlementsColumn" fieldOnly="true" property="IIQ_exceptionEntitlements" sortProperty="IIQ_exceptionEntitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="exceptionEntitlements-application" headerKey="application" property="exceptionEntitlements.application" renderer="SailPoint.certification.BaseCertificationGrid.renderApplication" sortProperty="exceptionEntitlements.application" stateId="exceptionEntitlements-application"/>
            <ColumnConfig dataIndex="exceptionEntitlements-instance" headerKey="instance" property="exceptionEntitlements.instance" sortProperty="exceptionEntitlements.instance" stateId="exceptionEntitlements-instance"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="account_name" property="IIQ_account" renderer="SailPoint.certification.BaseCertificationGrid.renderAccount" sortProperty="IIQ_account" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="entitlements" property="IIQ_entitlements" renderer="SailPoint.certification.BaseCertificationGrid.renderAppGranularityEntitlement" sortProperty="IIQ_entitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="accountKey" evaluator="sailpoint.web.view.certification.AccountKeyColumn" fieldOnly="true" property="IIQ_accountKey" sortProperty="IIQ_accountKey" stateId="accountKey"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailDataOwnerColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" evaluator="sailpoint.web.view.certification.ExceptionEntitlementsColumn" fieldOnly="true" property="IIQ_exceptionEntitlements" sortProperty="IIQ_exceptionEntitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="exceptionEntitlements-displayName" headerKey="account_name" property="exceptionEntitlements.displayName" renderer="SailPoint.certification.BaseCertificationGrid.renderGenericAccount" sortProperty="exceptionEntitlements.displayName" stateId="exceptionEntitlements-displayName"/>
            <ColumnConfig dataIndex="IIQ_identity" evaluator="sailpoint.web.view.certification.AccountGroupMembershipIdentityColumn" headerKey="identity" property="IIQ_identity" renderer="SailPoint.certification.BaseCertificationGrid.renderIdentity" sortProperty="IIQ_identity" stateId="IIQ_identity"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailEntitlementsColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="parent-targetName" fieldOnly="true" property="parent.targetName" sortProperty="parent.targetName" stateId="parent-targetName"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" evaluator="sailpoint.web.view.certification.ExceptionEntitlementsColumn" fieldOnly="true" property="IIQ_exceptionEntitlements" sortProperty="IIQ_exceptionEntitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="exceptionEntitlements-application" headerKey="application" property="exceptionEntitlements.application" renderer="SailPoint.certification.BaseCertificationGrid.renderApplication" sortProperty="exceptionEntitlements.application" stateId="exceptionEntitlements-application"/>
            <ColumnConfig dataIndex="exceptionEntitlements-instance" headerKey="instance" property="exceptionEntitlements.instance" sortProperty="exceptionEntitlements.instance" stateId="exceptionEntitlements-instance"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="account_name" property="IIQ_account" renderer="SailPoint.certification.BaseCertificationGrid.renderAccount" sortProperty="IIQ_account" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="attribute" property="IIQ_attribute" renderer="SailPoint.certification.BaseCertificationGrid.renderAccountAttribute" sortProperty="IIQ_attribute" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="IIQ_exceptionEntitlements" headerKey="entitlements" property="IIQ_entitlements" renderer="SailPoint.certification.BaseCertificationGrid.renderEntitlement" sortProperty="IIQ_entitlements" stateId="IIQ_exceptionEntitlements"/>
            <ColumnConfig dataIndex="accountKey" evaluator="sailpoint.web.view.certification.AccountKeyColumn" fieldOnly="true" property="IIQ_accountKey" sortProperty="IIQ_accountKey" stateId="accountKey"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailManagerRoleTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent.id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent.id"/>
            <ColumnConfig dataIndex="parent-targetName" fieldOnly="true" property="parent.targetName" sortProperty="parent.targetName" stateId="parent-targetName"/>
            <ColumnConfig dataIndex="IIQ_roleDetails" evaluator="sailpoint.web.view.certification.RoleDetailsColumn" fieldOnly="true" property="IIQ_roleDetails" sortProperty="IIQ_roleDetails" stateId="IIQ_roleDetails"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_entity_detected_roles_hdr_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices" width="27"/>
            <ColumnConfig dataIndex="bundle" fieldOnly="true" property="bundle" sortProperty="bundle" stateId="bundle"/>
            <ColumnConfig dataIndex="targetDisplayName" flex="1.0" headerKey="cert_entity_detected_roles_hdr_role" property="targetDisplayName" renderer="SailPoint.certification.BaseCertificationGrid.renderRoleDetails" sortProperty="targetDisplayName" stateId="targetDisplayName"/>
            <ColumnConfig dataIndex="IIQ_role-description" evaluator="sailpoint.web.view.certification.CertificationItemColumn" flex="3.0" headerKey="cert_entity_detected_roles_hdr_description" property="IIQ_role.description" renderer="SailPoint.certification.BaseCertificationGrid.renderDescription" sortProperty="role.description" stateId="IIQ_role-description"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailProfilesColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="profile-objectName" evaluator="sailpoint.web.view.certification.ProfileColumn" headerKey="profile" property="profile.objectName" renderer="SailPoint.certification.BaseCertificationGrid.renderProfile" sortProperty="profile.objectName" stateId="profile-objectName"/>
            <ColumnConfig dataIndex="profile-application" evaluator="sailpoint.web.view.certification.ProfileColumn" headerKey="application" property="profile.application" sortProperty="profile.application" stateId="profile-application"/>
            <ColumnConfig dataIndex="profile-objectDescription" evaluator="sailpoint.web.view.certification.ProfileColumn" headerKey="label_description" property="profile.objectDescription" renderer="SailPoint.grid.Util.renderDescription" sortProperty="profile.objectDescription" stateId="profile-objectDescription"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
            <ColumnConfig dataIndex="profile-constraints" evaluator="sailpoint.web.view.certification.ProfileColumn" fieldOnly="true" property="profile.constraints" sortProperty="profile.constraints" stateId="profile-constraints"/>
            <ColumnConfig dataIndex="profile-permissions" evaluator="sailpoint.web.view.certification.ProfileColumn" fieldOnly="true" property="profile.permissions" sortProperty="profile.permissions" stateId="profile-permissions"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailRelatedRolesColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="targetId" fieldOnly="true" property="targetId" sortProperty="targetId" stateId="targetId"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_item_role_comp_related_roles_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="snapshot-objectDisplayableName" evaluator="sailpoint.web.view.certification.RoleSnapshotColumn" headerKey="cert_item_role_comp_related_roles_name" property="snapshot.objectDisplayableName" renderer="SailPoint.certification.BaseCertificationGrid.renderRole" sortProperty="snapshot.objectDisplayableName" stateId="snapshot-objectDisplayableName"/>
            <ColumnConfig dataIndex="type" evaluator="sailpoint.web.view.certification.ItemTypeColumn" headerKey="cert_item_role_comp_related_roles_type" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="snapshot-objectDescription" evaluator="sailpoint.web.view.certification.RoleSnapshotColumn" headerKey="cert_item_role_comp_related_roles_desc" property="snapshot.objectDescription" sortProperty="snapshot.objectDescription" stateId="snapshot-objectDescription"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailScopesAndCapabilitiesColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_item_role_comp_grant_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="targetName" headerKey="cert_item_role_comp_grant_name" property="targetName" sortProperty="targetName" stateId="targetName"/>
            <ColumnConfig dataIndex="type" evaluator="sailpoint.web.view.certification.ItemTypeColumn" headerKey="cert_item_role_comp_grant_type" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="snapshot-objectDescription" evaluator="sailpoint.web.view.certification.RoleSnapshotColumn" headerKey="cert_item_role_comp_grant_desc" property="snapshot.objectDescription" sortProperty="snapshot.objectDescription" stateId="snapshot-objectDescription"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="certificationDetailViolationTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="parent-targetName" fieldOnly="true" property="parent.targetName" sortProperty="parent.targetName" stateId="parent-targetName"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
            <ColumnConfig dataIndex="IIQ_decisionChoices" evaluator="sailpoint.web.view.certification.CertificationItemDecisionColumn" headerKey="cert_decision" property="IIQ_decisionChoices" renderer="SailPoint.certification.BaseCertificationGrid.renderButtons" sortProperty="IIQ_decisionChoices" stateId="IIQ_decisionChoices"/>
            <ColumnConfig dataIndex="violation-policyName" evaluator="sailpoint.web.view.certification.CertificationViolationColumn" headerKey="cert_detail_violation_col_policy" property="violation.policyName" sortProperty="violation.policyName" stateId="violation-policyName"/>
            <ColumnConfig dataIndex="violation-owner" evaluator="sailpoint.web.view.certification.CertificationViolationColumn" headerKey="cert_detail_violation_col_owner" property="violation.owner" sortProperty="violation.owner" stateId="violation-owner"/>
            <ColumnConfig dataIndex="violation-constraint" evaluator="sailpoint.web.view.certification.CertificationViolationColumn" headerKey="cert_detail_violation_col_rule" property="violation.constraint" renderer="SailPoint.ruleExpander" sortProperty="violation.constraint" stateId="violation-constraint"/>
            <ColumnConfig dataIndex="violation-summary" evaluator="sailpoint.web.view.certification.CertificationViolationColumn" headerKey="cert_detail_violation_col_summary" property="violation.summary" renderer="SailPoint.grid.Util.renderRawValue" sortProperty="violation.summary" stateId="violation-summary"/>
            <ColumnConfig dataIndex="IIQ_continuous" evaluator="sailpoint.web.view.certification.ContinuousStateColumn" headerKey="cert_details_hdr_due_date" property="IIQ_continuous" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousDateColumn" sortProperty="IIQ_continuous" stateId="IIQ_continuous"/>
            <ColumnConfig dataIndex="violation_renderer" evaluator="sailpoint.web.view.certification.CertificationViolationColumn" fieldOnly="true" property="violation.renderer" sortProperty="violation.renderer" stateId="violation_renderer"/>
          </List>
        </value>
      </entry>
      <entry key="certificationEntityDataOwnerTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="identity" headerKey="cert_item_tbl_header_data_item" hideable="true" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.BaseCertificationGrid.renderStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="IIQ_dataOwnerEntityDesc" headerKey="cert_item_tbl_header_description" hideable="true" property="IIQ_dataOwnerEntityDesc" renderer="SailPoint.certification.BaseCertificationGrid.renderDescription" sortProperty="IIQ_dataOwnerEntityDesc" stateId="IIQ_dataOwnerEntityDesc"/>
            <ColumnConfig dataIndex="IIQ_hasDelegations" fieldOnly="true" property="IIQ_hasDelegations" sortProperty="IIQ_hasDelegations" stateId="IIQ_hasDelegations"/>
          </List>
        </value>
      </entry>
      <entry key="certificationEntityTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="identity" headerKey="cert_item_tbl_header_identity" hideable="true" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
            <ColumnConfig dataIndex="firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.BaseCertificationGrid.renderStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="compositeScore" headerKey="cert_item_tbl_header_compositescore" hideable="true" property="compositeScore" sortProperty="compositeScore" sortable="true" stateId="compositeScore"/>
            <ColumnConfig dataIndex="IIQ_changes_detected" headerKey="changes_detected" hideable="true" renderer="SailPoint.certification.BaseCertificationGrid.renderChanges" sortProperty="IIQ_changes_detected" sortable="true" stateId="IIQ_changes_detected"/>
            <ColumnConfig dataIndex="IIQ_hasDelegations" fieldOnly="true" property="IIQ_hasDelegations" sortProperty="IIQ_hasDelegations" stateId="IIQ_hasDelegations"/>
          </List>
        </value>
      </entry>
      <entry key="certificationEventsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" flex="1.0" headerKey="cert_event_tbl_header_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="type" headerKey="cert_event_tbl_header_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="attributeName" headerKey="cert_event_tbl_header_attribute_name" hideable="true" property="attributeName" sortProperty="attributeName" sortable="true" stateId="attributeName"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="cert_event_tbl_header_owner" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="disabled" headerKey="cert_event_tbl_header_disabled" hideable="true" property="disabled" renderer="SailPoint.Monitor.Grid.CertificationEvents.renderDisabled" sortProperty="disabled" sortable="true" stateId="disabled"/>
          </List>
        </value>
      </entry>
      <entry key="certificationItemDataOwnerTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="decision" headerKey="decision" property="IIQ_calculatedStatus" renderer="SailPoint.certification.WorksheetGrid.renderButtons" sortProperty="IIQ_calculatedStatus" stateId="decision"/>
            <ColumnConfig dataIndex="IIQ_description" headerKey="cert_item_tbl_header_data_item" hideable="true" percentWidth="30" property="IIQ_description" renderer="SailPoint.certification.WorksheetGrid.renderDescription" sortProperty="IIQ_description" sortable="true" stateId="IIQ_description"/>
            <ColumnConfig dataIndex="IIQ_entitlementDescription" fieldOnly="true" headerKey="cert_item_tbl_header_entitlement_description" hidden="true" property="IIQ_entitlementDescription" sortProperty="IIQ_entitlementDescription" stateId="IIQ_entitlementDescription"/>
            <ColumnConfig dataIndex="exceptionApplication" headerKey="cert_item_tbl_header_application" hideable="true" property="exceptionApplication" renderer="SailPoint.certification.WorksheetGrid.renderApplication" sortProperty="exceptionApplication" sortable="true" stateId="exceptionApplication"/>
            <ColumnConfig dataIndex="instance" headerKey="instance" hideable="true" property="exceptionEntitlements.instance" sortProperty="exceptionEntitlements.instance" stateId="instance"/>
            <ColumnConfig dataIndex="Identity-displayName" headerKey="cert_item_tbl_header_identity" hideable="true" property="Identity.displayName" sortProperty="Identity.displayName" sortable="true" stateId="Identity-displayName"/>
            <ColumnConfig dataIndex="Identity-manager-displayName" headerKey="manager" hideable="true" property="Identity.manager.displayName" sortProperty="Identity.manager.displayName" sortable="true" stateId="Identity-manager-displayName"/>
            <ColumnConfig dataIndex="Identity-firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="Identity.firstname" sortProperty="Identity.firstname" sortable="true" stateId="Identity-firstname"/>
            <ColumnConfig dataIndex="Identity-lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="Identity.lastname" sortProperty="Identity.lastname" sortable="true" stateId="Identity-lastname"/>
            <ColumnConfig dataIndex="exceptionEntitlements-displayName" headerKey="cert_item_tbl_header_accountDisplayName" hideable="true" property="exceptionEntitlements.displayName" sortProperty="exceptionEntitlements.displayName" sortable="true" stateId="exceptionEntitlements-displayName"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.WorksheetGrid.renderCommentStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="changes_detected" headerKey="changes_detected" hidden="true" hideable="true" renderer="SailPoint.certification.WorksheetGrid.renderChanges" sortProperty="IIQ_changes_detected" sortable="true" stateId="changes_detected"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="targetName" fieldOnly="true" name="parent-identity" stateId="targetName"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="parent-schemaObjectType" headerKey="cert_item_tbl_header_type" hidden="true" hideable="true" property="parent.schemaObjectType" sortProperty="parent.schemaObjectType" sortable="true" stateId="parent-schemaObjectType"/>
            <ColumnConfig dataIndex="accountKey" fieldOnly="true" property="IIQ_accountKey" sortProperty="IIQ_accountKey" stateId="accountKey"/>
          </List>
        </value>
      </entry>
      <entry key="certificationItemTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="decision" flex="1.0" headerKey="decision" property="IIQ_calculatedStatus" renderer="SailPoint.certification.WorksheetGrid.renderButtons" sortProperty="IIQ_calculatedStatus" stateId="decision"/>
            <ColumnConfig dataIndex="parent-identity" headerKey="cert_item_tbl_header_identity" hideable="true" property="parent.identity" sortProperty="parent.identity" sortable="true" stateId="parent-identity"/>
            <ColumnConfig dataIndex="parent-firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="parent.firstname" sortProperty="parent.firstname" sortable="true" stateId="parent-firstname"/>
            <ColumnConfig dataIndex="parent-lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="parent.lastname" sortProperty="parent.lastname" sortable="true" stateId="parent-lastname"/>
            <ColumnConfig dataIndex="IIQ_description" flex="2.0" headerKey="cert_item_tbl_header_description" hideable="true" property="IIQ_description" renderer="SailPoint.certification.WorksheetGrid.renderDescription" sortProperty="IIQ_description" sortable="true" stateId="IIQ_description"/>
            <ColumnConfig dataIndex="IIQ_entitlementDescription" fieldOnly="true" headerKey="cert_item_tbl_header_full_description" hidden="true" property="IIQ_entitlementDescription" renderer="SailPoint.certification.WorksheetGrid.emptyRenderer" sortProperty="IIQ_entitlementDescription" stateId="IIQ_entitlementDescription"/>
            <ColumnConfig dataIndex="exceptionApplication" headerKey="cert_item_tbl_header_application" hideable="true" property="exceptionApplication" renderer="SailPoint.certification.WorksheetGrid.renderApplication" sortProperty="exceptionApplication" stateId="exceptionApplication"/>
            <ColumnConfig dataIndex="exceptionEntitlements-instance" headerKey="cert_item_tbl_header_instance" hidden="true" hideable="true" property="exceptionEntitlements.instance" sortProperty="exceptionEntitlements.instance" sortable="true" stateId="exceptionEntitlements-instance"/>
            <ColumnConfig dataIndex="IIQ_applicationDescription" fieldOnly="true" headerKey="cert_item_tbl_header_application_description" hidden="true" property="IIQ_applicationDescription" renderer="SailPoint.certification.WorksheetGrid.emptyRenderer" sortProperty="IIQ_applicationDescription" stateId="IIQ_applicationDescription"/>
            <ColumnConfig dataIndex="exceptionEntitlements-nativeIdentity" headerKey="cert_item_tbl_header_accountid" hidden="true" hideable="true" property="exceptionEntitlements.nativeIdentity" sortProperty="exceptionEntitlements.nativeIdentity" sortable="true" stateId="exceptionEntitlements-nativeIdentity"/>
            <ColumnConfig dataIndex="exceptionEntitlements-displayName" headerKey="cert_item_tbl_header_accountDisplayName" hideable="true" property="exceptionEntitlements.displayName" sortProperty="exceptionEntitlements.displayName" stateId="exceptionEntitlements-displayName"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.WorksheetGrid.renderCommentStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="parent-compositeScore" headerKey="cert_item_tbl_header_compositescore" hideable="true" property="parent.compositeScore" sortProperty="parent.compositeScore" sortable="true" stateId="parent-compositeScore"/>
            <ColumnConfig dataIndex="IIQ_changes_detected" headerKey="changes_detected" hideable="true" renderer="SailPoint.certification.WorksheetGrid.renderChanges" sortProperty="IIQ_changes_detected" sortable="true" stateId="IIQ_changes_detected"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="accountKey" fieldOnly="true" property="IIQ_accountKey" sortProperty="IIQ_accountKey" stateId="accountKey"/>
          </List>
        </value>
      </entry>
      <entry key="certificationRemediationTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="action-workItem" fieldOnly="true" property="action.workItem" sortProperty="action.workItem" stateId="action-workItem"/>
            <ColumnConfig dataIndex="action-completionState" fieldOnly="true" property="action.completionState" sortProperty="action.completionState" stateId="action-completionState"/>
            <ColumnConfig dataIndex="action-remediationCompleted" headerKey="status" hideable="true" property="action.remediationCompleted" sortProperty="action.remediationCompleted" sortable="true" stateId="action-remediationCompleted"/>
            <ColumnConfig dataIndex="action-ownerName" headerKey="recipient" hideable="true" property="action.ownerName" sortProperty="action.ownerName" sortable="true" stateId="action-ownerName"/>
            <ColumnConfig dataIndex="action-actorName" headerKey="label_requester" hideable="true" property="action.actorName" sortProperty="action.actorName" sortable="true" stateId="action-actorName"/>
            <ColumnConfig dataIndex="parent-targetName" headerKey="target" hideable="true" property="parent.targetName" sortProperty="parent.targetName" sortable="true" stateId="parent-targetName"/>
            <ColumnConfig dataIndex="targetName" fieldOnly="true" property="targetName" sortProperty="targetName" stateId="targetName"/>
            <ColumnConfig dataIndex="IIQ_revoked" headerKey="revoked" hideable="true" sortProperty="IIQ_revoked" sortable="true" stateId="IIQ_revoked"/>
            <ColumnConfig dataIndex="action-remediationAction" headerKey="type" hideable="true" property="action.remediationAction" renderer="SailPoint.Certification.RemediationGrid.renderRemediationStatus" sortProperty="action.remediationAction" sortable="true" stateId="action-remediationAction"/>
            <ColumnConfig dataIndex="parent-certification-created" headerKey="expiration" hideable="true" property="parent.certification.created" sortProperty="parent.certification.created" sortable="true" stateId="parent-certification-created"/>
            <ColumnConfig dataIndex="action-description" headerKey="details" hideable="true" property="action.description" sortProperty="action.description" sortable="true" stateId="action-description"/>
          </List>
        </value>
      </entry>
      <entry key="certificationScheduleTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" headerKey="description" hideable="true" property="description" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="nextExecution" headerKey="next_execution" hideable="true" property="nextExecution" sortProperty="nextExecution" sortable="true" stateId="nextExecution"/>
            <ColumnConfig dataIndex="lastExecution" headerKey="last_execution" hideable="true" property="lastExecution" sortProperty="lastExecution" sortable="true" stateId="lastExecution"/>
            <ColumnConfig dataIndex="latestResult" headerKey="result" hideable="true" property="latestResult" renderer="renderStatus" sortProperty="latestResult" sortable="true" stateId="latestResult"/>
            <ColumnConfig dataIndex="launcher" headerKey="owner" hideable="true" property="launcher" sortProperty="launcher" sortable="true" stateId="launcher"/>
            <ColumnConfig dataIndex="statusId" fieldOnly="true" property="statusId" sortProperty="statusId" stateId="statusId"/>
          </List>
        </value>
      </entry>
      <entry key="certificationsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" flex="1.0" headerKey="cert_sched_groups_col_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="ownerDisplayName" headerKey="cert_sched_groups_col_owner" hideable="true" property="ownerDisplayName" sortProperty="owner.name" sortable="true" stateId="ownerDisplayName"/>
            <ColumnConfig dataIndex="status" headerKey="cert_sched_groups_col_status" hideable="true" property="status" sortProperty="status" sortable="true" stateId="status"/>
            <ColumnConfig dataIndex="percentComplete" headerKey="cert_sched_groups_col_percent_complete" hideable="true" property="percentComplete" sortProperty="percentComplete" sortable="true" stateId="percentComplete"/>
            <ColumnConfig dataIndex="created" headerKey="cert_sched_groups_col_created" hideable="true" property="created" renderer="SailPoint.Date.DateTimeRenderer" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="tags" headerKey="cert_sched_groups_col_tags" hideable="true" property="tags" sortProperty="tags" stateId="tags"/>
          </List>
        </value>
      </entry>
      <entry key="continuousCertificationEntityDataOwnerTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="identity" headerKey="cert_item_tbl_header_data_item" hideable="true" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
            <ColumnConfig dataIndex="overdueDate" dateStyle="short" headerKey="cert_item_tbl_header_overdue" hideable="true" property="overdueDate" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousStateColumn" sortProperty="overdueDate" sortable="true" stateId="overdueDate" timeStyle="none"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.BaseCertificationGrid.renderStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="IIQ_dataOwnerEntityDesc" headerKey="cert_item_tbl_header_description" hideable="true" property="IIQ_dataOwnerEntityDesc" sortProperty="IIQ_dataOwnerEntityDesc" stateId="IIQ_dataOwnerEntityDesc"/>
            <ColumnConfig dataIndex="IIQ_continuousStateName" fieldOnly="true" property="IIQ_continuousStateName" sortProperty="IIQ_continuousStateName" stateId="IIQ_continuousStateName"/>
            <ColumnConfig dataIndex="IIQ_hasDelegations" fieldOnly="true" property="IIQ_hasDelegations" sortProperty="IIQ_hasDelegations" stateId="IIQ_hasDelegations"/>
          </List>
        </value>
      </entry>
      <entry key="continuousCertificationEntityTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="identity" headerKey="cert_item_tbl_header_identity" hideable="true" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
            <ColumnConfig dataIndex="firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="overdueDate" dateStyle="short" headerKey="cert_item_tbl_header_overdue" hideable="true" property="overdueDate" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousStateColumn" sortProperty="overdueDate" sortable="true" stateId="overdueDate" timeStyle="none"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.BaseCertificationGrid.renderStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="compositeScore" headerKey="cert_item_tbl_header_compositescore" hideable="true" property="compositeScore" sortProperty="compositeScore" sortable="true" stateId="compositeScore"/>
            <ColumnConfig dataIndex="IIQ_changes_detected" headerKey="changes_detected" hideable="true" renderer="SailPoint.certification.BaseCertificationGrid.renderChanges" sortProperty="IIQ_changes_detected" sortable="true" stateId="IIQ_changes_detected"/>
            <ColumnConfig dataIndex="IIQ_continuousStateName" fieldOnly="true" property="IIQ_continuousStateName" sortProperty="IIQ_continuousStateName" stateId="IIQ_continuousStateName"/>
            <ColumnConfig dataIndex="IIQ_hasDelegations" fieldOnly="true" property="IIQ_hasDelegations" sortProperty="IIQ_hasDelegations" stateId="IIQ_hasDelegations"/>
          </List>
        </value>
      </entry>
      <entry key="continuousCertificationItemDataOwnerTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="decision" headerKey="decision" property="IIQ_calculatedStatus" renderer="SailPoint.certification.WorksheetGrid.renderButtons" sortProperty="IIQ_calculatedStatus" stateId="decision"/>
            <ColumnConfig dataIndex="IIQ_description" headerKey="cert_item_tbl_header_data_item" hideable="true" percentWidth="30" property="IIQ_description" renderer="SailPoint.certification.WorksheetGrid.renderDescription" sortProperty="IIQ_description" sortable="true" stateId="IIQ_description"/>
            <ColumnConfig dataIndex="IIQ_entitlementDescription" fieldOnly="true" headerKey="cert_item_tbl_header_entitlement_description" hidden="true" property="IIQ_entitlementDescription" sortProperty="IIQ_entitlementDescription" stateId="IIQ_entitlementDescription"/>
            <ColumnConfig dataIndex="exceptionApplication" headerKey="cert_item_tbl_header_application" hideable="true" property="exceptionApplication" renderer="SailPoint.certification.WorksheetGrid.renderApplication" sortProperty="exceptionApplication" sortable="true" stateId="exceptionApplication"/>
            <ColumnConfig dataIndex="instance" headerKey="instance" hideable="true" property="exceptionEntitlements.instance" sortProperty="exceptionEntitlements.instance" stateId="instance"/>
            <ColumnConfig dataIndex="Identity-displayName" headerKey="cert_item_tbl_header_identity" hideable="true" property="Identity.displayName" sortProperty="Identity.displayName" sortable="true" stateId="Identity-displayName"/>
            <ColumnConfig dataIndex="Identity-manager-displayName" headerKey="manager" hideable="true" property="Identity.manager.displayName" sortProperty="Identity.manager.displayName" sortable="true" stateId="Identity-manager-displayName"/>
            <ColumnConfig dataIndex="Identity-firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="Identity.firstname" sortProperty="Identity.firstname" sortable="true" stateId="Identity-firstname"/>
            <ColumnConfig dataIndex="Identity-lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="Identity.lastname" sortProperty="Identity.lastname" sortable="true" stateId="Identity-lastname"/>
            <ColumnConfig dataIndex="exceptionEntitlements-displayName" headerKey="cert_item_tbl_header_accountDisplayName" hideable="true" property="exceptionEntitlements.displayName" sortProperty="exceptionEntitlements.displayName" sortable="true" stateId="exceptionEntitlements-displayName"/>
            <ColumnConfig dataIndex="overdueDate" dateStyle="short" headerKey="cert_item_tbl_header_overdue" hideable="true" percentWidth="20" property="overdueDate" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousStateColumn" sortProperty="overdueDate" sortable="true" stateId="overdueDate" timeStyle="none"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.WorksheetGrid.renderCommentStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="changes_detected" headerKey="changes_detected" hidden="true" hideable="true" renderer="SailPoint.certification.WorksheetGrid.renderChanges" sortProperty="IIQ_changes_detected" sortable="true" stateId="changes_detected"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="targetName" fieldOnly="true" name="parent-identity" stateId="targetName"/>
            <ColumnConfig dataIndex="accountKey" fieldOnly="true" property="IIQ_accountKey" sortProperty="IIQ_accountKey" stateId="accountKey"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="IIQ_decisionHistory" evaluator="sailpoint.web.view.certification.CertificationDecisionHistoryColumn" fieldOnly="true" property="IIQ_decisionHistory" sortProperty="IIQ_decisionHistory" stateId="IIQ_decisionHistory"/>
          </List>
        </value>
      </entry>
      <entry key="continuousCertificationItemTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="decision" headerKey="decision" percentWidth="15" property="IIQ_calculatedStatus" renderer="SailPoint.certification.WorksheetGrid.renderButtons" sortProperty="IIQ_calculatedStatus" stateId="decision"/>
            <ColumnConfig dataIndex="parent-identity" headerKey="cert_item_tbl_header_identity" hideable="true" property="parent.identity" sortProperty="parent.identity" sortable="true" stateId="parent-identity"/>
            <ColumnConfig dataIndex="parent-firstname" headerKey="cert_item_tbl_header_firstname" hideable="true" property="parent.firstname" sortProperty="parent.firstname" sortable="true" stateId="parent-firstname"/>
            <ColumnConfig dataIndex="parent-lastname" headerKey="cert_item_tbl_header_lastname" hideable="true" property="parent.lastname" sortProperty="parent.lastname" sortable="true" stateId="parent-lastname"/>
            <ColumnConfig dataIndex="IIQ_description" headerKey="cert_item_tbl_header_description" hideable="true" percentWidth="40" property="IIQ_description" renderer="SailPoint.certification.WorksheetGrid.renderDescription" sortProperty="IIQ_description" sortable="true" stateId="IIQ_description"/>
            <ColumnConfig dataIndex="IIQ_entitlementDescription" fieldOnly="true" headerKey="cert_item_tbl_header_entitlement_description" hidden="true" property="IIQ_entitlementDescription" sortProperty="IIQ_entitlementDescription" stateId="IIQ_entitlementDescription"/>
            <ColumnConfig dataIndex="exceptionApplication" headerKey="cert_item_tbl_header_application" hideable="true" property="exceptionApplication" renderer="SailPoint.certification.WorksheetGrid.renderApplication" sortProperty="exceptionApplication" stateId="exceptionApplication"/>
            <ColumnConfig dataIndex="exceptionEntitlements-instance" headerKey="cert_item_tbl_header_instance" hidden="true" hideable="true" property="exceptionEntitlements.instance" sortProperty="exceptionEntitlements.instance" sortable="true" stateId="exceptionEntitlements-instance"/>
            <ColumnConfig dataIndex="IIQ_applicationDescription" fieldOnly="true" headerKey="cert_item_tbl_header_application_description" hidden="true" property="IIQ_applicationDescription" sortProperty="IIQ_applicationDescription" stateId="IIQ_applicationDescription"/>
            <ColumnConfig dataIndex="exceptionEntitlements-nativeIdentity" headerKey="cert_item_tbl_header_accountid" hidden="true" hideable="true" property="exceptionEntitlements.nativeIdentity" sortProperty="exceptionEntitlements.nativeIdentity" sortable="true" stateId="exceptionEntitlements-nativeIdentity"/>
            <ColumnConfig dataIndex="exceptionEntitlements-displayName" headerKey="cert_item_tbl_header_accountDisplayName" hideable="true" property="exceptionEntitlements.displayName" sortProperty="exceptionEntitlements.displayName" stateId="exceptionEntitlements-displayName"/>
            <ColumnConfig dataIndex="overdueDate" dateStyle="short" headerKey="cert_item_tbl_header_overdue" hideable="true" percentWidth="20" property="overdueDate" renderer="SailPoint.certification.BaseCertificationGrid.renderCertContinuousStateColumn" sortProperty="overdueDate" sortable="true" stateId="overdueDate" timeStyle="none"/>
            <ColumnConfig dataIndex="summaryStatus" headerKey="status" hideable="true" property="summaryStatus" renderer="SailPoint.certification.WorksheetGrid.renderCommentStatus" sortProperty="summaryStatus" sortable="true" stateId="summaryStatus"/>
            <ColumnConfig dataIndex="parent-compositeScore" headerKey="cert_item_tbl_header_compositescore" hideable="true" property="parent.compositeScore" sortProperty="parent.compositeScore" sortable="true" stateId="parent-compositeScore"/>
            <ColumnConfig dataIndex="IIQ_changes_detected" headerKey="changes_detected" hideable="true" renderer="SailPoint.certification.WorksheetGrid.renderChanges" sortProperty="IIQ_changes_detected" sortable="true" stateId="IIQ_changes_detected"/>
            <ColumnConfig dataIndex="parent-id" fieldOnly="true" property="parent.id" sortProperty="parent.id" stateId="parent-id"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="accountKey" fieldOnly="true" property="IIQ_accountKey" sortProperty="IIQ_accountKey" stateId="accountKey"/>
          </List>
        </value>
      </entry>
      <entry key="customCertificationEntityPageInclude"/>
      <entry key="dashApplicationStatisticsColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" percentWidth="60" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="scorecard-created" headerKey="label_statistics_updated" hideable="true" property="scorecard.created" sortProperty="scorecard.created" sortable="true" stateId="scorecard-created"/>
            <ColumnConfig dataIndex="scorecard-attributes" fieldOnly="true" property="scorecard.attributes" sortProperty="scorecard.attributes" stateId="scorecard-attributes"/>
            <ColumnConfig dataIndex="scorecard-id" fieldOnly="true" property="scorecard.id" sortProperty="scorecard.id" stateId="scorecard-id"/>
          </List>
        </value>
      </entry>
      <entry key="dashCertificationCompletionColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="shortName" headerKey="name" hideable="true" percentWidth="45" property="shortName" sortProperty="shortName" sortable="true" stateId="shortName"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="phase" headerKey="phase" hideable="true" property="phase" sortProperty="phase" sortable="true" stateId="phase"/>
            <ColumnConfig dataIndex="statistics-itemPercentComplete" headerKey="percentage_complete" hideable="true" property="statistics.itemPercentComplete" renderer="renderPercent" sortProperty="statistics.itemPercentComplete" sortable="true" stateId="statistics-itemPercentComplete"/>
            <ColumnConfig dataIndex="expiration" headerKey="due" hideable="true" property="expiration" sortProperty="expiration" sortable="true" stateId="expiration"/>
            <ColumnConfig dataIndex="certifiers" fieldOnly="true" stateId="certifiers"/>
            <ColumnConfig dataIndex="completedItems" fieldOnly="true" stateId="completedItems"/>
            <ColumnConfig dataIndex="totalItems" fieldOnly="true" stateId="totalItems"/>
          </List>
        </value>
      </entry>
      <entry key="dashboardAccessRequestGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" hidden="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="dash_access_req_col_id" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="requesterDisplayName" headerKey="dash_access_req_col_requester" hideable="true" property="requesterDisplayName" sortProperty="requesterDisplayName" sortable="true" stateId="requesterDisplayName"/>
            <ColumnConfig dataIndex="targetDisplayName" headerKey="dash_access_req_col_identity" hideable="true" property="targetDisplayName" sortProperty="targetDisplayName" sortable="true" stateId="targetDisplayName"/>
            <ColumnConfig dataIndex="created" headerKey="dash_access_req_col_request_date" hideable="true" property="created" sortProperty="created" sortable="true" stateId="created" width="100"/>
            <ColumnConfig dataIndex="executionStatus" headerKey="dash_access_req_col_status" hideable="true" property="executionStatus" sortProperty="executionStatus" sortable="true" stateId="executionStatus"/>
            <ColumnConfig dataIndex="externalTicketId" headerKey="dash_access_req_col_external_ticket" hideable="true" property="externalTicketId" sortProperty="externalTicketId" sortable="true" stateId="externalTicketId"/>
          </List>
        </value>
      </entry>
      <entry key="dashboardCertificationsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="dash_cert_groups_col_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="ownerDisplayName" headerKey="dash_cert_groups_col_owner" hideable="true" property="ownerDisplayName" sortProperty="owner.name" sortable="true" stateId="ownerDisplayName"/>
            <ColumnConfig dataIndex="percentComplete" headerKey="dash_cert_groups_col_status" hideable="true" property="percentComplete" sortProperty="percentComplete" sortable="true" stateId="percentComplete"/>
            <ColumnConfig dataIndex="created" headerKey="dash_cert_groups_col_created" hideable="true" property="created" renderer="SailPoint.Date.DateTimeRenderer" sortProperty="created" sortable="true" stateId="created"/>
          </List>
        </value>
      </entry>
      <entry key="dashboardInboxTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="work_item_hdr_id" hidden="true" hideable="true" property="name" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="id" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" flex="1.0" headerKey="name" hideable="true" percentWidth="50" property="description" secondarySort="name" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" property="type" secondarySort="name" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="requester-name" headerKey="label_requester" hideable="true" property="requester.name" secondarySort="name" sortProperty="requester.name" sortable="true" stateId="requester-name"/>
            <ColumnConfig dataIndex="workgroupName" headerKey="inbox_hdr_workgroup" hidden="true" hideable="true" property="workgroupName" secondarySort="name" sortProperty="owner.workgroup,owner.name" sortable="true" stateId="workgroupName"/>
            <ColumnConfig dataIndex="assignee-name" headerKey="inbox_hdr_assignee" hidden="true" hideable="true" property="assignee.name" renderer="SailPoint.workitem.renderAssigneeColumn" secondarySort="name" sortProperty="assignee.name" sortable="true" stateId="assignee-name"/>
            <ColumnConfig dataIndex="created" headerKey="created" hideable="true" property="created" secondarySort="name" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="expiration" headerKey="expiration" hideable="true" property="expiration" secondarySort="name" sortProperty="expiration" sortable="true" stateId="expiration"/>
            <ColumnConfig dataIndex="level" headerKey="priority" hideable="true" property="level" renderer="SailPoint.workitem.renderPriorityColumn" secondarySort="name" sortProperty="level" sortable="true" stateId="level"/>
            <ColumnConfig dataIndex="identityRequestId" headerKey="work_item_hdr_access_request_id" hidden="true" hideable="true" property="identityRequestId" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="name" sortProperty="identityRequestId" sortable="true" stateId="identityRequestId"/>
            <ColumnConfig dataIndex="certificationId" fieldOnly="true" property="certification" sortProperty="certification" stateId="certificationId"/>
            <ColumnConfig dataIndex="isDelegationForwardDisabled" fieldOnly="true" stateId="isDelegationForwardDisabled"/>
            <ColumnConfig dataIndex="limitReassignments" fieldOnly="true" stateId="limitReassignments"/>
          </List>
        </value>
      </entry>
      <entry key="dashboardMyAccessRequestGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" hidden="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="dash_access_req_col_id" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="priority" headerKey="dash_access_req_col_priority" hideable="true" property="priority" sortProperty="priority" sortable="true" stateId="priority"/>
            <ColumnConfig dataIndex="type" headerKey="dash_access_req_col_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="requesterDisplayName" headerKey="dash_access_req_col_requester" hideable="true" property="requesterDisplayName" sortProperty="requesterDisplayName" sortable="true" stateId="requesterDisplayName"/>
            <ColumnConfig dataIndex="targetDisplayName" headerKey="dash_access_req_col_requestee" hideable="true" property="targetDisplayName" sortProperty="targetDisplayName" sortable="true" stateId="targetDisplayName"/>
            <ColumnConfig dataIndex="created" headerKey="dash_access_req_col_request_date" hideable="true" property="created" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="executionStatus" headerKey="dash_access_req_col_status" hideable="true" property="executionStatus" sortProperty="executionStatus" sortable="true" stateId="executionStatus"/>
            <ColumnConfig dataIndex="externalTicketId" headerKey="dash_access_req_col_external_ticket" hideable="true" property="externalTicketId" sortProperty="externalTicketId" sortable="true" stateId="externalTicketId"/>
          </List>
        </value>
      </entry>
      <entry key="dashboardOutboxTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="work_item_hdr_id" hidden="true" hideable="true" property="name" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="id" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" flex="1.0" headerKey="name" hideable="true" percentWidth="50" property="description" secondarySort="name" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" property="type" secondarySort="name" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="owner-name" headerKey="owner" hideable="true" property="owner.name" secondarySort="name" sortProperty="owner.name" sortable="true" stateId="owner-name"/>
            <ColumnConfig dataIndex="created" headerKey="created" hideable="true" property="created" secondarySort="name" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="expiration" headerKey="expiration" hideable="true" property="expiration" secondarySort="name" sortProperty="expiration" sortable="true" stateId="expiration"/>
            <ColumnConfig dataIndex="level" headerKey="priority" hideable="true" property="level" renderer="SailPoint.workitem.renderPriorityColumn" secondarySort="name" sortProperty="level" sortable="true" stateId="level"/>
            <ColumnConfig dataIndex="identityRequestId" headerKey="work_item_hdr_access_request_id" hidden="true" hideable="true" property="identityRequestId" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="name" sortProperty="identityRequestId" sortable="true" stateId="identityRequestId"/>
            <ColumnConfig dataIndex="certificationId" fieldOnly="true" property="certification" sortProperty="certification" stateId="certificationId"/>
          </List>
        </value>
      </entry>
      <entry key="dashboardSignoffStatusTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="work_item_hdr_id" hidden="true" hideable="true" property="name" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="id" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" headerKey="name" hideable="true" percentWidth="35" property="description" secondarySort="name" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="owner-name" headerKey="owner" hideable="true" property="owner.name" secondarySort="name" sortProperty="owner.name" sortable="true" stateId="owner-name"/>
            <ColumnConfig dataIndex="created" headerKey="date" hideable="true" property="created" secondarySort="name" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="TaskResult-name" headerKey="title_task_result" hideable="true" percentWidth="30" property="TaskResult.name" secondarySort="name" sortProperty="TaskResult.name" sortable="true" stateId="TaskResult-name"/>
            <ColumnConfig dataIndex="isCertification" fieldOnly="true" stateId="isCertification"/>
            <ColumnConfig dataIndex="owner-id" fieldOnly="true" stateId="owner-id"/>
            <ColumnConfig dataIndex="targetId" fieldOnly="true" stateId="targetId"/>
          </List>
        </value>
      </entry>
      <entry key="dataOwnerExclusions">
        <value>
          <List>
            <ColumnConfig dataIndex="exceptionApplication" headerKey="cert_exclusions_col_application" hideable="true" property="exceptionApplication" sortProperty="exceptionApplication" sortable="true" stateId="exceptionApplication"/>
            <ColumnConfig dataIndex="targetName" headerKey="cert_exclusions_col_account" hideable="true" property="targetName" sortProperty="targetName" sortable="true" stateId="targetName"/>
            <ColumnConfig dataIndex="subType" headerKey="cert_exclusions_col_type" hideable="true" property="subType" sortProperty="subType" sortable="true" stateId="subType"/>
            <ColumnConfig dataIndex="SPT_description" headerKey="cert_exclusions_col_desc" hideable="true" renderer="SailPoint.certification.ExclusionsGrid.renderDescription" sortProperty="SPT_description" sortable="true" stateId="SPT_description"/>
            <ColumnConfig dataIndex="parent-explanation" headerKey="cert_exclusions_col_reason" hideable="true" property="parent.explanation" sortProperty="parent.explanation" stateId="parent-explanation"/>
          </List>
        </value>
      </entry>
      <entry key="debugApplicationActivityGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="timeStamp" dateStyle="short" headerKey="Date" property="timeStamp" sortProperty="timeStamp" sortable="true" stateId="timeStamp" width="150"/>
            <ColumnConfig dataIndex="action" headerKey="Action" property="action" sortProperty="action" sortable="true" stateId="action" width="150"/>
            <ColumnConfig dataIndex="identityName" headerKey="Identity" property="identityName" sortProperty="identityName" sortable="true" stateId="identityName" width="200"/>
            <ColumnConfig dataIndex="target" headerKey="Target" property="target" sortProperty="target" sortable="true" stateId="target" width="300"/>
          </List>
        </value>
      </entry>
      <entry key="debugAuthenticationQuestionGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="question" headerKey="Question" property="question" sortProperty="question" sortable="true" stateId="question" width="300"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugCertificationGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="type" headerKey="Type" property="type" sortProperty="type" sortable="true" stateId="type" width="200"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
            <ColumnConfig dataIndex="signed" headerKey="Signed" property="signed" sortProperty="signed" sortable="true" stateId="signed" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugDatabaseVersionGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="200"/>
            <ColumnConfig dataIndex="systemVersion" headerKey="System Version" property="systemVersion" sortProperty="systemVersion" sortable="true" stateId="systemVersion" width="150"/>
            <ColumnConfig dataIndex="schemaVersion" headerKey="Schema Version" property="schemaVersion" sortProperty="schemaVersion" sortable="true" stateId="schemaVersion" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugIdentityEntitlementGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="identity" headerKey="Identity" property="identity.name" sortProperty="identity.name" sortable="true" stateId="identity" width="250"/>
            <ColumnConfig dataIndex="app" headerKey="Application" property="application.name" sortProperty="application.name" sortable="true" stateId="app" width="250"/>
            <ColumnConfig dataIndex="accountid" headerKey="AccountId" property="nativeIdentity" sortProperty="nativeIdentity" sortable="true" stateId="accountid" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="value" headerKey="Value" property="value" sortProperty="value" sortable="true" stateId="value" width="250"/>
            <ColumnConfig dataIndex="aggregationState" headerKey="State" property="aggregationState" sortProperty="aggregationState" sortable="true" stateId="aggregationState" width="250"/>
            <ColumnConfig dataIndex="type" headerKey="Type" property="type" sortProperty="type" sortable="true" stateId="type" width="250"/>
          </List>
        </value>
      </entry>
      <entry key="debugIdentityHistoryItemGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="identity-name" headerKey="Identity" property="identity.name" sortProperty="identity.name" sortable="true" stateId="identity-name" width="200"/>
            <ColumnConfig dataIndex="type" headerKey="Type" property="type" sortProperty="type" sortable="true" stateId="type" width="200"/>
            <ColumnConfig dataIndex="status" headerKey="Status" property="status" sortProperty="status" sortable="true" stateId="status" width="150"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugIdentityHistoryItemSearchProperties" value="id,identity.name,identity.displayName"/>
      <entry key="debugIdentityRequestGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="RequestId" property="name" sortProperty="name" sortable="true" stateId="name" width="150"/>
            <ColumnConfig dataIndex="targetDisplayName" headerKey="Identity" property="targetDisplayName" sortProperty="targetDisplayName" sortable="true" stateId="targetDisplayName" width="200"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Launched" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="endDate" dateStyle="short" headerKey="Completed" property="endDate" sortProperty="endDate" sortable="true" stateId="endDate" width="150"/>
            <ColumnConfig dataIndex="verified" dateStyle="short" headerKey="Verified" property="verified" sortProperty="verified" sortable="true" stateId="verified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugIdentitySearchProperties" value="id,name,displayName"/>
      <entry key="debugIdentitySnapshotGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="identityName" sortProperty="identityName" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugLinkSearchProperties" value="id,name,displayName"/>
      <entry key="debugManagedAttributeGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="attribute" headerKey="Attribute" property="attribute" sortProperty="attribute" sortable="true" stateId="attribute" width="100"/>
            <ColumnConfig dataIndex="value" headerKey="Value" property="value" sortProperty="value" sortable="true" stateId="value" width="200"/>
            <ColumnConfig dataIndex="application" headerKey="Application" property="application.name" sortProperty="application.name" sortable="true" stateId="application" width="200"/>
            <ColumnConfig dataIndex="type" headerKey="Type" property="type" sortProperty="type" sortable="true" stateId="type" width="100"/>
            <ColumnConfig dataIndex="requestable" headerKey="Requestable" property="requestable" sortProperty="requestable" sortable="true" stateId="requestable" width="50"/>
            <ColumnConfig dataIndex="owner" headerKey="Owner" property="owner.name" sortProperty="owner.name" sortable="true" stateId="owner" width="150"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugObjectGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugPolicyViolationGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="identityName" headerKey="Identity" property="identity.name" sortProperty="identity.name" stateId="identityName" width="200"/>
            <ColumnConfig dataIndex="policyName" headerKey="Policy" property="policyName" sortProperty="policyName" stateId="policyName" width="250"/>
            <ColumnConfig dataIndex="constraintName" headerKey="Constraint" property="constraintName" sortProperty="constraintName" stateId="constraintName" width="250"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugProcessLogGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="processName" headerKey="Process Name" property="processName" sortProperty="processName" sortable="true" stateId="processName" width="150"/>
            <ColumnConfig dataIndex="stepName" headerKey="Step Name" property="stepName" sortProperty="stepName" sortable="true" stateId="stepName" width="150"/>
            <ColumnConfig dataIndex="stepDuration" headerKey="Step Duration" property="stepDuration" sortProperty="stepDuration" sortable="true" stateId="stepDuration" width="50"/>
            <ColumnConfig dataIndex="approvalName" headerKey="Approval Name" property="approvalName" sortProperty="approvalName" sortable="true" stateId="approvalName" width="150"/>
            <ColumnConfig dataIndex="owner" headerKey="Owner" property="owner.name" sortProperty="owner.name" sortable="true" stateId="owner" width="150"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugQuickLinkOptionsGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="dynamicScope" headerKey="DynamicScope" property="dynamicScope.name" sortProperty="dynamicScope.name" sortable="true" stateId="dynamicScope" width="200"/>
            <ColumnConfig dataIndex="quickLink" headerKey="QuickLink" property="quickLink.name" sortProperty="quickLink.name" sortable="true" stateId="quickLink" width="200"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugRequestGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="definition" headerKey="Definition" property="definition.name" sortProperty="definition.name" sortable="true" stateId="definition" width="200"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="completed" dateStyle="short" headerKey="Completed" property="completed" sortProperty="completed" sortable="true" stateId="completed" width="150"/>
            <ColumnConfig dataIndex="launched" dateStyle="short" headerKey="Launched" property="launched" sortProperty="launched" sortable="true" stateId="launched" width="150"/>
            <ColumnConfig dataIndex="nextLaunch" dateStyle="short" headerKey="Next Launch" property="nextLaunch" sortProperty="nextLaunch" sortable="true" stateId="nextLaunch" width="150"/>
            <ColumnConfig dataIndex="retryCount" headerKey="Retries" property="retryCount" sortProperty="retryCount" sortable="true" stateId="retryCount" width="100"/>
          </List>
        </value>
      </entry>
      <entry key="debugRoleChangeEventGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="bundle_id" headerKey="Bundle Id" property="bundleId" sortProperty="bundleId" sortable="true" stateId="bundle_id" width="250"/>
            <ColumnConfig dataIndex="bundle_name" headerKey="Bundle Name" property="bundleName" sortProperty="bundleName" sortable="true" stateId="bundle_name" width="250"/>
            <ColumnConfig dataIndex="bundle_deleted" headerKey="Bundle Deleted" property="bundleDeleted" sortProperty="bundleDeleted" sortable="true" stateId="bundle_deleted" width="250"/>
          </List>
        </value>
      </entry>
      <entry key="debugRoleIndexGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="role" headerKey="Role" property="bundle.name" sortProperty="bundle.name" sortable="true" stateId="role" width="200"/>
            <ColumnConfig dataIndex="assignedCount" headerKey="Assigned Count" property="assignedCount" sortProperty="assignedCount" sortable="true" stateId="assignedCount" width="100"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugRoleScorecardGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="role" headerKey="Role" property="role.name" sortProperty="role.name" sortable="true" stateId="role" width="200"/>
            <ColumnConfig dataIndex="members" headerKey="Members" property="members" sortProperty="members" sortable="true" stateId="members" width="100"/>
            <ColumnConfig dataIndex="membersWithAdditionalEntitlements" headerKey="Members with Additional Entitlements" property="membersWithAdditionalEntitlements" sortProperty="membersWithAdditionalEntitlements" sortable="true" stateId="membersWithAdditionalEntitlements" width="100"/>
            <ColumnConfig dataIndex="membersWithMissingRequiredRoles" headerKey="Members with Missing Required Roles" property="membersWithMissingRequiredRoles" sortProperty="membersWithMissingRequiredRoles" sortable="true" stateId="membersWithMissingRequiredRoles" width="100"/>
            <ColumnConfig dataIndex="detected" headerKey="Identities Detected" property="detected" sortProperty="detected" sortable="true" stateId="detected" width="100"/>
            <ColumnConfig dataIndex="detectedAsExceptions" headerKey="Identities Detected as Exceptions" property="detectedAsExceptions" sortProperty="detectedAsExceptions" sortable="true" stateId="detectedAsExceptions" width="100"/>
            <ColumnConfig dataIndex="provisionedEntitlements" headerKey="Provisioned Entitlements" property="provisionedEntitlements" sortProperty="provisionedEntitlements" sortable="true" stateId="provisionedEntitlements" width="100"/>
            <ColumnConfig dataIndex="permittedEntitlements" headerKey="Permitted Entitlements" property="permittedEntitlements" sortProperty="permittedEntitlements" sortable="true" stateId="permittedEntitlements" width="100"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugScorecardGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="identity" headerKey="Identity" property="identity.name" sortProperty="identity.name" sortable="true" stateId="identity" width="200"/>
            <ColumnConfig dataIndex="compositeScore" headerKey="Score" property="compositeScore" sortProperty="compositeScore" sortable="true" stateId="compositeScore" width="100"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugSyslogEventGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="quickKey" headerKey="Incident Code" property="quickKey" sortProperty="quickKey" sortable="true" stateId="quickKey" width="110"/>
            <ColumnConfig dataIndex="eventLevel" headerKey="Level" property="eventLevel" sortProperty="eventLevel" sortable="true" stateId="eventLevel" width="75"/>
            <ColumnConfig dataIndex="message" headerKey="Message" property="message" sortProperty="message" sortable="true" stateId="message" width="400"/>
          </List>
        </value>
      </entry>
      <entry key="debugTaskScheduleGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="lastExecution" dateStyle="short" headerKey="Last Execution" property="lastExecution" sortProperty="lastExecution" sortable="true" stateId="lastExecution" width="150"/>
            <ColumnConfig dataIndex="nextExecution" dateStyle="short" headerKey="Next Execution" property="nextExecution" sortProperty="nextExecution" sortable="true" stateId="nextExecution" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugUIPreferencesGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="owner" headerKey="Identity" property="owner.name" sortProperty="owner.name" sortable="true" stateId="owner" width="200"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugWorkItemArchiveGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="description" headerKey="Description" property="description" sortProperty="description" sortable="true" stateId="description" width="400"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="debugWorkItemGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Id" property="id" sortProperty="id" sortable="true" stateId="id" width="250"/>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name" width="250"/>
            <ColumnConfig dataIndex="description" headerKey="Description" property="description" sortProperty="description" sortable="true" stateId="description" width="400"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="Created" property="created" sortProperty="created" sortable="true" stateId="created" width="150"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="Modified" property="modified" sortProperty="modified" sortable="true" stateId="modified" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="disableRoleEditorImpactAnalysis" value="false"/>
      <entry key="disabledSuggestExtendedAttributes"/>
      <entry key="entitlementCatalogTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="application" headerKey="application" hideable="true" property="application.name" secondarySort="displayableName" sortProperty="application.name" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="attribute" headerKey="attribute" hideable="true" property="attribute" sortProperty="attribute" sortable="true" stateId="attribute"/>
            <ColumnConfig dataIndex="displayableName" headerKey="display_name" hideable="true" property="displayableName" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="value" headerKey="name" hidden="true" hideable="true" property="value" sortProperty="value" sortable="true" stateId="value"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="description" headerKey="description" hideable="true" property="attributes" renderer="SailPoint.grid.Util.renderDescription" sortProperty="attributes" stateId="description"/>
            <ColumnConfig dataIndex="owner" headerKey="owner" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner"/>
            <ColumnConfig dataIndex="requestable" headerKey="explanation_col_requestable" hideable="true" property="requestable" renderer="SailPoint.grid.Util.renderBoolean" sortProperty="requestable" sortable="true" stateId="requestable"/>
            <ColumnConfig dataIndex="modified" headerKey="last_refreshed" hidden="true" hideable="true" property="modified" sortProperty="modified" sortable="true" stateId="modified"/>
          </List>
        </value>
      </entry>
      <entry key="explanationTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="type" headerKey="explanation_col_type" hideable="true" percentWidth="10" property="type" renderer="SailPoint.Define.Grid.Explanation.renderExplanation" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="attribute" headerKey="explanation_col_attribute" hideable="true" percentWidth="15" property="attribute" renderer="SailPoint.Define.Grid.Explanation.renderExplanation" sortProperty="attribute" sortable="true" stateId="attribute"/>
            <ColumnConfig dataIndex="displayableName" headerKey="explanation_col_display_name" hideable="true" percentWidth="15" property="displayableName" renderer="SailPoint.Define.Grid.Explanation.renderExplanation" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="value" headerKey="explanation_col_value" hideable="true" percentWidth="15" property="value" renderer="SailPoint.Define.Grid.Explanation.renderExplanation" sortProperty="value" sortable="true" stateId="value"/>
            <ColumnConfig dataIndex="explanation" headerKey="explanation_col_explanation" hideable="true" percentWidth="40" renderer="SailPoint.Define.Grid.Explanation.renderExplanation" stateId="explanation"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="explanation_col_owner" hideable="true" percentWidth="15" property="owner.displayName" renderer="SailPoint.Define.Grid.Explanation.renderExplanation" sortProperty="owner.displayName" sortable="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="requestable" headerKey="explanation_col_requestable" hideable="true" percentWidth="10" property="requestable" renderer="SailPoint.Define.Grid.Explanation.renderRequestable" sortProperty="requestable" sortable="true" stateId="requestable"/>
            <ColumnConfig dataIndex="purview" fieldOnly="true" property="purview" sortProperty="purview" stateId="purview"/>
          </List>
        </value>
      </entry>
      <entry key="formsColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="Form Id" property="id" sortProperty="id" sortable="true" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="Form Name" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="type" headerKey="Type" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="description" headerKey="Description" property="description" sortProperty="description" sortable="true" stateId="description"/>
          </List>
        </value>
      </entry>
      <entry key="groupTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="factoryAttribute" headerKey="attribute" hideable="true" property="factoryAttribute" sortProperty="factoryAttribute" sortable="true" stateId="factoryAttribute"/>
            <ColumnConfig dataIndex="description" headerKey="description" hideable="true" percentWidth="45" property="description" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="enabled" headerKey="status" hideable="true" property="enabled" renderer="renderStatus" sortProperty="enabled" sortable="true" stateId="enabled"/>
          </List>
        </value>
      </entry>
      <entry key="identityEntitlementGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="isGroup" fieldOnly="true" stateId="isGroup"/>
            <ColumnConfig dataIndex="aggregationState" fieldOnly="true" property="aggregationState" sortProperty="aggregationState" stateId="aggregationState"/>
            <ColumnConfig dataIndex="entitlementDescription" fieldOnly="true" stateId="entitlementDescription"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="startDate" fieldOnly="true" property="startDate" sortProperty="startDate" stateId="startDate"/>
            <ColumnConfig dataIndex="endDate" fieldOnly="true" property="endDate" sortProperty="endDate" stateId="endDate"/>
            <ColumnConfig dataIndex="name" headerKey="label_attribute" hideable="true" percentWidth="20" property="name" renderer="SailPoint.Define.Grid.IdentityEntitlements.renderAttribute" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="displayValue" headerKey="entitlement" hideable="true" percentWidth="35" renderer="SailPoint.Define.Grid.IdentityEntitlements.renderValue" stateId="displayValue"/>
            <ColumnConfig dataIndex="application" headerKey="label_application" hideable="true" percentWidth="15" property="application.name" sortProperty="application.name" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="nativeIdentity" headerKey="account_name" hideable="true" percentWidth="15" property="displayName" sortProperty="displayName" sortable="true" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="instance" headerKey="instance" hidden="true" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="lastCertName" headerKey="identity_entitlements_cert_last" hidden="true" hideable="true" property="certificationItem.parent.certification.name" sortProperty="certificationItem.parent.certification.name" stateId="lastCertName"/>
            <ColumnConfig dataIndex="lastCertDate" dateStyle="short" headerKey="identity_entitlements_cert_last_date" hidden="true" hideable="true" property="certificationItem.modified" sortProperty="certificationItem.modified" stateId="lastCertDate"/>
            <ColumnConfig dataIndex="hasPendingRequest" headerKey="identity_entitlements_has_pending_request" hidden="true" hideable="true" stateId="hasPendingRequest"/>
            <ColumnConfig dataIndex="pendingRequestId" headerKey="identity_entitlements_request_id" hidden="true" hideable="true" property="requestItem.identityRequest.name" sortProperty="requestItem.identityRequest.name" stateId="pendingRequestId"/>
          </List>
        </value>
      </entry>
      <entry key="identityEntitlementRoleGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="identityId" fieldOnly="true" property="identity.id" sortProperty="identity.id" stateId="identityId"/>
            <ColumnConfig dataIndex="startDate" fieldOnly="true" property="startDate" sortProperty="startDate" stateId="startDate"/>
            <ColumnConfig dataIndex="endDate" fieldOnly="true" property="endDate" sortProperty="endDate" stateId="endDate"/>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="roleId" fieldOnly="true" stateId="roleId"/>
            <ColumnConfig dataIndex="roleType" fieldOnly="true" stateId="roleType"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="Bundle-displayableName" headerKey="displayable_name" hideable="true" percentWidth="20" property="Bundle.displayableName" renderer="SailPoint.Define.Grid.IdentityEntitlementRoles.renderValue" sortProperty="Bundle.displayableName" sortable="true" stateId="Bundle-displayableName"/>
            <ColumnConfig dataIndex="roleDescription" headerKey="label_description" hideable="true" percentWidth="30" renderer="SailPoint.Define.Grid.IdentityEntitlementRoles.renderDescription" stateId="roleDescription"/>
            <ColumnConfig dataIndex="assigner" headerKey="identity_role_col_assigned_by" hideable="true" percentWidth="10" property="assigner" sortProperty="assigner" stateId="assigner"/>
            <ColumnConfig dataIndex="allowedBy" headerKey="identity_role_col_permittedBy" hideable="true" percentWidth="10" stateId="allowedBy"/>
            <ColumnConfig dataIndex="acquired" headerKey="identity_role_col_acquired" hideable="true" percentWidth="10" stateId="acquired"/>
            <ColumnConfig dataIndex="lastCertName" headerKey="identity_entitlements_cert_last" hidden="true" hideable="true" property="certificationItem.parent.certification.name" sortProperty="certificationItem.parent.certification.name" stateId="lastCertName"/>
            <ColumnConfig dataIndex="lastCertDate" dateStyle="short" headerKey="identity_entitlements_cert_last_date" hidden="true" hideable="true" property="certificationItem.modified" sortProperty="certificationItem.modified" stateId="lastCertDate"/>
            <ColumnConfig dataIndex="hasPendingRequest" headerKey="identity_entitlements_has_pending_request" hidden="true" hideable="true" stateId="hasPendingRequest"/>
            <ColumnConfig dataIndex="pendingRequestId" headerKey="identity_entitlements_request_id" hidden="true" hideable="true" property="requestItem.identityRequest.name" sortProperty="requestItem.identityRequest.name" stateId="pendingRequestId"/>
            <ColumnConfig dataIndex="application" headerKey="identity_entitlements_applications" hideable="true" percentWidth="10" stateId="application"/>
            <ColumnConfig dataIndex="account" headerKey="identity_entitlements_accounts" hideable="true" percentWidth="10" stateId="account"/>
            <ColumnConfig dataIndex="assignmentId" fieldOnly="true" property="assignmentId" sortProperty="assignmentId" stateId="assignmentId"/>
            <ColumnConfig dataIndex="assignmentNote" headerKey="identity_role_col_assignment_note" hidden="true" hideable="true" property="assignmentNote" sortProperty="assignmentNote" stateId="assignmentNote"/>
          </List>
        </value>
      </entry>
      <entry key="identityExclusions">
        <value>
          <List>
            <ColumnConfig dataIndex="parent-identity" headerKey="cert_exclusions_col_identity" hideable="true" property="parent.identity" sortProperty="parent.identity" sortable="true" stateId="parent-identity"/>
            <ColumnConfig dataIndex="type" headerKey="cert_exclusions_col_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="SPT_description" headerKey="cert_exclusions_col_desc" hideable="true" renderer="SailPoint.certification.ExclusionsGrid.renderDescription" sortProperty="SPT_description" sortable="true" stateId="SPT_description"/>
            <ColumnConfig dataIndex="parent-explanation" headerKey="cert_exclusions_col_reason" hideable="true" property="parent.explanation" sortProperty="parent.explanation" stateId="parent-explanation"/>
          </List>
        </value>
      </entry>
      <entry key="identityHistoryByItemTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="action" fieldOnly="true" property="action" sortProperty="action" stateId="action"/>
            <ColumnConfig dataIndex="status" headerKey="cert_item_view_hist_grid_hdr_action" property="status" sortProperty="status" stateId="status" width="120"/>
            <ColumnConfig dataIndex="actor" headerKey="cert_item_view_hist_grid_hdr_actor" property="actor" sortProperty="actor" stateId="actor" width="140"/>
            <ColumnConfig dataIndex="entryDate" dateStyle="short" headerKey="cert_item_view_hist_grid_hdr_date" property="entryDate" sortProperty="entryDate" sortable="true" stateId="entryDate" width="180"/>
            <ColumnConfig dataIndex="comments" headerKey="msgs.cert_item_view_hist_grid_hdr_comments" property="comments" renderer="SailPoint.IdentityHistoryPanel.stylizeComments" sortProperty="comments" stateId="comments"/>
          </List>
        </value>
      </entry>
      <entry key="identityHistoryTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="status" headerKey="identity_history_grid_hdr_status" hideable="true" property="status" renderer="SailPoint.Identity.History.renderStatus" sortProperty="status" sortable="true" stateId="status" width="65"/>
            <ColumnConfig dataIndex="certificationType" headerKey="identity_history_grid_hdr_cert_type" hideable="true" property="certificationType" renderer="SailPoint.Identity.History.renderType" sortProperty="certificationType" sortable="true" stateId="certificationType" width="45"/>
            <ColumnConfig dataIndex="description" headerKey="identity_history_grid_hdr_description" hideable="true" property="description" sortProperty="description" stateId="description" width="125"/>
            <ColumnConfig dataIndex="application" headerKey="identity_history_grid_hdr_application" hideable="true" property="application" sortProperty="application" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="instance" headerKey="identity_history_grid_hdr_instance" hidden="true" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="account" headerKey="identity_history_grid_hdr_account" hideable="true" property="account" sortProperty="account" sortable="true" stateId="account"/>
            <ColumnConfig dataIndex="actor" headerKey="identity_history_grid_hdr_actor" hideable="true" property="actor" sortProperty="actor" sortable="true" stateId="actor"/>
            <ColumnConfig dataIndex="entryDate" dateStyle="short" headerKey="identity_history_grid_hdr_entry_date" hideable="true" property="entryDate" sortProperty="entryDate" sortable="true" stateId="entryDate" width="120"/>
            <ColumnConfig dataIndex="comments" headerKey="identity_history_grid_hdr_comments" hideable="true" property="comments" sortProperty="comments" stateId="comments"/>
          </List>
        </value>
      </entry>
      <entry key="identityRequestOperationAllowedValues">
        <value>
          <List>
            <SelectItem label="provisioning_plan_op_create" value="Create"/>
            <SelectItem label="provisioning_plan_op_modify" value="Modify"/>
            <SelectItem label="provisioning_plan_op_delete" value="Delete"/>
            <SelectItem label="provisioning_plan_op_disable" value="Disable"/>
            <SelectItem label="provisioning_plan_op_enable" value="Enable"/>
            <SelectItem label="provisioning_plan_op_lock" value="Lock"/>
            <SelectItem label="provisioning_plan_op_unlock" value="Unlock"/>
            <SelectItem label="provisioning_plan_op_set" value="Set"/>
            <SelectItem label="provisioning_plan_op_add" value="Add"/>
            <SelectItem label="provisioning_plan_op_remove" value="Remove"/>
          </List>
        </value>
      </entry>
      <entry key="identityRequestStateAllowedValues">
        <value>
          <List>
            <SelectItem label="identity_request_state_initialize" value="Initialize"/>
            <SelectItem label="identity_request_state_approve" value="Approve"/>
            <SelectItem label="identity_request_state_provision" value="Provision"/>
            <SelectItem label="identity_request_state_notify" value="Notify"/>
            <SelectItem label="identity_request_state_finalize" value="Finalize"/>
          </List>
        </value>
      </entry>
      <entry key="identitySearchAttributes" value="displayName,name,firstname,lastname"/>
      <entry key="identityTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="idents_grid_hdr_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="firstname" headerKey="idents_grid_hdr_first_name" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="idents_grid_hdr_last_name" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="manager-displayName" headerKey="idents_grid_hdr_manager" hideable="true" property="manager.displayName" sortProperty="manager.displayName" sortable="true" stateId="manager-displayName"/>
            <ColumnConfig dataIndex="assignedRoleSummary" headerKey="idents_grid_hdr_assigned_roles" hideable="true" property="assignedRoleSummary" sortProperty="assignedRoleSummary" stateId="assignedRoleSummary"/>
            <ColumnConfig dataIndex="bundleSummary" headerKey="idents_grid_hdr_detected_roles" hideable="true" property="bundleSummary" sortProperty="bundleSummary" stateId="bundleSummary"/>
            <ColumnConfig dataIndex="scorecard-compositeScore" headerKey="idents_grid_hdr_composite_score" hideable="true" property="scorecard.compositeScore" renderer="SailPoint.Define.Grid.Identity.renderScore" sortProperty="scorecard.compositeScore" sortable="true" stateId="scorecard-compositeScore"/>
            <ColumnConfig dataIndex="lastRefresh" dateStyle="short" headerKey="idents_grid_hdr_last_refresh" hideable="true" property="lastRefresh" sortProperty="lastRefresh" sortable="true" stateId="lastRefresh"/>
            <ColumnConfig dataIndex="managerStatus" fieldOnly="true" property="managerStatus" sortProperty="managerStatus" stateId="managerStatus"/>
            <ColumnConfig dataIndex="status" headerKey="status" hideable="true" property="status" sortProperty="status" sortable="true" stateId="status"/>
            <ColumnConfig dataIndex="correlated" headerKey="Authoritative?" hideable="true" property="correlated" sortProperty="correlated" sortable="true" stateId="correlated"/>
          </List>
        </value>
      </entry>
      <entry key="identityViewAttributes" value="name,firstname,lastname,email,manager,department,location,empId,region,jobtitle,costcenter,status"/>
      <entry key="lcmCreateIdentityProvisioningPolicyRequiredFields">
        <value>
          <List>
            <Field displayName="Username" name="name" required="true" type="string"/>
          </List>
        </value>
      </entry>
      <entry key="lcmPopulationSearchGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="idents_grid_hdr_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="firstname" headerKey="idents_grid_hdr_first_name" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="idents_grid_hdr_last_name" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="manager-displayName" headerKey="idents_grid_hdr_manager" hideable="true" property="manager.displayName" sortProperty="manager.displayName" sortable="true" stateId="manager-displayName"/>
            <ColumnConfig dataIndex="scorecard-compositeScore" headerKey="idents_grid_hdr_composite_score" hideable="true" property="scorecard.compositeScore" renderer="SailPoint.LCM.RequestAccess.scoreRenderer" sortProperty="scorecard.compositeScore" sortable="true" stateId="scorecard-compositeScore"/>
            <ColumnConfig dataIndex="scorecard-totalViolations" headerKey="idents_grid_hdr_policy_violations" hideable="true" property="scorecard.totalViolations" sortProperty="scorecard.totalViolations" sortable="true" stateId="scorecard-totalViolations"/>
            <ColumnConfig dataIndex="managerStatus" fieldOnly="true" property="managerStatus" sortProperty="managerStatus" stateId="managerStatus"/>
            <ColumnConfig dataIndex="IIQ_color" fieldOnly="true" stateId="IIQ_color"/>
          </List>
        </value>
      </entry>
      <entry key="lcmSearchIdentityAttributes" value="manager"/>
      <entry key="lcmSearchRoleAttributes" value="none"/>
      <entry key="manageWorkItemsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="work_item_hdr_id" hideable="true" property="name" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="id" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" flex="1.0" headerKey="name" hideable="true" percentWidth="50" property="description" secondarySort="name" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" property="type" secondarySort="name" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="requester-name" headerKey="label_requester" hideable="true" property="requester.name" secondarySort="name" sortProperty="requester.name" sortable="true" stateId="requester-name"/>
            <ColumnConfig dataIndex="requester-id" fieldOnly="true" hidden="true" property="requester.id" sortProperty="requester.id" stateId="requester-id"/>
            <ColumnConfig dataIndex="workgroupName" headerKey="inbox_hdr_workgroup" hidden="true" hideable="true" property="workgroupName" secondarySort="name" sortProperty="owner.workgroup,owner.name" sortable="true" stateId="workgroupName"/>
            <ColumnConfig dataIndex="owner-name" headerKey="owner" hideable="true" property="owner.name" secondarySort="name" sortProperty="owner.name" sortable="true" stateId="owner-name"/>
            <ColumnConfig dataIndex="owner-id" fieldOnly="true" hidden="true" property="owner.id" sortProperty="owner.id" stateId="owner-id"/>
            <ColumnConfig dataIndex="assignee-name" headerKey="inbox_hdr_assignee" hideable="true" property="assignee.name" renderer="SailPoint.workitem.renderAssigneeColumn" secondarySort="name" sortProperty="assignee.name" sortable="true" stateId="assignee-name"/>
            <ColumnConfig dataIndex="assignee-id" fieldOnly="true" hidden="true" property="assignee.id" sortProperty="assignee.id" stateId="assignee-id"/>
            <ColumnConfig dataIndex="created" headerKey="created" hideable="true" property="created" secondarySort="name" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="expiration" headerKey="expiration" hideable="true" property="expiration" secondarySort="name" sortProperty="expiration" sortable="true" stateId="expiration"/>
            <ColumnConfig dataIndex="wakeUpDate" headerKey="next_event_date" hideable="true" property="wakeUpDate" secondarySort="name" sortProperty="wakeUpDate" sortable="true" stateId="wakeUpDate"/>
            <ColumnConfig dataIndex="level" headerKey="priority" hideable="true" property="level" renderer="SailPoint.workitem.renderPriorityColumn" secondarySort="name" sortProperty="level" sortable="true" stateId="level"/>
            <ColumnConfig dataIndex="reminders" headerKey="reminders" hideable="true" property="reminders" secondarySort="name" sortProperty="reminders" sortable="true" stateId="reminders"/>
            <ColumnConfig dataIndex="escalationCount" headerKey="escalations" hideable="true" property="escalationCount" secondarySort="name" sortProperty="escalationCount" sortable="true" stateId="escalationCount"/>
            <ColumnConfig dataIndex="identityRequestId" headerKey="work_item_hdr_access_request_id" hideable="true" property="identityRequestId" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="name" sortProperty="identityRequestId" sortable="true" stateId="identityRequestId" width="150"/>
            <ColumnConfig dataIndex="certificationId" fieldOnly="true" property="certification" sortProperty="certification" stateId="certificationId"/>
            <ColumnConfig dataIndex="isDelegationForwardDisabled" fieldOnly="true" stateId="isDelegationForwardDisabled"/>
          </List>
        </value>
      </entry>
      <entry key="managedAttributeAllKeys">
        <value>
          <List>
            <ColumnConfig dataIndex="id" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="displayName" property="displayName" sortProperty="displayName" stateId="displayName"/>
            <ColumnConfig dataIndex="application-id" property="application.id" sortProperty="application.id" stateId="application-id"/>
            <ColumnConfig dataIndex="application-name" property="application.name" sortProperty="application.name" stateId="application-name"/>
            <ColumnConfig dataIndex="type" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="attribute" property="attribute" sortProperty="attribute" stateId="attribute"/>
            <ColumnConfig dataIndex="value" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="requestable" property="requestable" sortProperty="requestable" stateId="requestable"/>
          </List>
        </value>
      </entry>
      <entry key="managedAttributeAttrTypeOnly">
        <value>
          <List>
            <ColumnConfig dataIndex="attribute" property="attribute" sortProperty="attribute" stateId="attribute"/>
            <ColumnConfig dataIndex="type" property="type" sortProperty="type" stateId="type"/>
          </List>
        </value>
      </entry>
      <entry key="managedAttributeAttrTypeWithApp">
        <value>
          <List>
            <ColumnConfig dataIndex="attribute" property="attribute" sortProperty="attribute" stateId="attribute"/>
            <ColumnConfig dataIndex="type" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="application-name" property="application.name" sortProperty="application.name" stateId="application-name"/>
            <ColumnConfig dataIndex="application-id" property="application.id" sortProperty="application.id" stateId="application-id"/>
          </List>
        </value>
      </entry>
      <entry key="manualCorrelationIdentityTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="identity_correlation_identity_grid_col_name" hideable="true" property="name" renderer="SailPoint.IdentityDetailPopup.renderIdentityDetailGrid" sortProperty="name" sortable="true" stateId="name" width="160"/>
            <ColumnConfig dataIndex="firstname" headerKey="identity_correlation_identity_grid_col_fname" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname" width="120"/>
            <ColumnConfig dataIndex="lastname" headerKey="identity_correlation_identity_grid_col_lname" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname" width="120"/>
            <ColumnConfig dataIndex="correlated" editorClass="checkcolumn" headerKey="identity_correlation_identity_grid_col_correlated" hideable="true" property="correlated" sortProperty="correlated" sortable="true" stateId="correlated" width="145"/>
            <ColumnConfig dataIndex="manager-name" headerKey="identity_correlation_identity_grid_col_mgr" hideable="true" property="manager.name" sortProperty="manager.name" sortable="true" stateId="manager-name" width="130"/>
            <ColumnConfig dataIndex="email" headerKey="identity_correlation_identity_grid_col_email" hideable="true" property="email" sortProperty="email" sortable="true" stateId="email" width="290"/>
            <ColumnConfig dataIndex="inactive" headerKey="identity_correlation_identity_grid_col_inactive" hideable="true" property="inactive" sortProperty="inactive" sortable="true" stateId="inactive" width="100"/>
            <ColumnConfig dataIndex="lastRefresh" dateStyle="short" headerKey="identity_correlation_identity_grid_col_last_refresh" hideable="true" property="lastRefresh" renderer="SailPoint.Date.DateTimeRenderer" sortProperty="lastRefresh" sortable="true" stateId="lastRefresh" width="230"/>
          </List>
        </value>
      </entry>
      <entry key="miningResultsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="completed" headerKey="date_complete" hideable="true" property="completed" sortProperty="completed" sortable="true" stateId="completed"/>
            <ColumnConfig dataIndex="completionStatus" headerKey="result" hideable="true" property="completionStatus" renderer="renderStatus" sortProperty="completionStatus" sortable="true" stateId="completionStatus"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="label_started_by" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="definition-subType" headerKey="type" hideable="true" property="definition.subType" sortProperty="definition.subType" sortable="true" stateId="definition-subType"/>
            <ColumnConfig dataIndex="statusId" fieldOnly="true" stateId="statusId"/>
          </List>
        </value>
      </entry>
      <entry key="miningTemplatesTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" percentWidth="30" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="subType" headerKey="type" hideable="true" property="subType" sortProperty="subType" sortable="true" stateId="subType"/>
            <ColumnConfig dataIndex="owner-name" headerKey="owner" hideable="true" property="owner.name" sortProperty="owner.name" sortable="true" stateId="owner-name"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="created" hideable="true" property="created" sortProperty="created" sortable="true" stateId="created"/>
          </List>
        </value>
      </entry>
      <entry key="myAccessRequestGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" hidden="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="dash_access_req_col_id" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="priority" headerKey="dash_access_req_col_priority" hideable="true" property="priority" sortProperty="priority" sortable="true" stateId="priority"/>
            <ColumnConfig dataIndex="type" headerKey="dash_access_req_col_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="requesterDisplayName" headerKey="dash_access_req_col_requester" hideable="true" property="requesterDisplayName" sortProperty="requesterDisplayName" sortable="true" stateId="requesterDisplayName"/>
            <ColumnConfig dataIndex="targetDisplayName" headerKey="dash_access_req_col_requestee" hideable="true" property="targetDisplayName" sortProperty="targetDisplayName" sortable="true" stateId="targetDisplayName"/>
            <ColumnConfig dataIndex="created" headerKey="dash_access_req_col_request_date" hideable="true" property="created" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="state" headerKey="dash_access_req_col_current_step" hideable="true" property="state" sortProperty="state" sortable="true" stateId="state"/>
            <ColumnConfig dataIndex="endDate" headerKey="dash_access_req_col_completed" hideable="true" property="endDate" sortProperty="endDate" sortable="true" stateId="endDate"/>
            <ColumnConfig dataIndex="executionStatus" headerKey="dash_access_req_col_status" hideable="true" property="executionStatus" sortProperty="executionStatus" sortable="true" stateId="executionStatus"/>
            <ColumnConfig dataIndex="externalTicketId" headerKey="dash_access_req_col_external_ticket" hideable="true" property="externalTicketId" sortProperty="externalTicketId" sortable="true" stateId="externalTicketId"/>
          </List>
        </value>
      </entry>
      <entry key="myCertificationsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="shortName" headerKey="description" hideable="true" property="shortName" sortProperty="shortName" sortable="true" stateId="shortName"/>
            <ColumnConfig dataIndex="itemPercentComplete" headerKey="per_complete" hideable="true" property="statistics.itemPercentComplete" renderer="SailPoint.Manage.Grid.Certifications.renderPercent" sortProperty="statistics.itemPercentComplete" sortable="true" stateId="itemPercentComplete"/>
            <ColumnConfig dataIndex="totalItems" fieldOnly="true" property="statistics.totalItems" sortProperty="statistics.totalItems" stateId="totalItems"/>
            <ColumnConfig dataIndex="completedItems" fieldOnly="true" property="statistics.completedItems" sortProperty="statistics.completedItems" stateId="completedItems"/>
            <ColumnConfig dataIndex="phase" headerKey="phase" hideable="true" property="phase" sortProperty="phase" sortable="true" stateId="phase"/>
            <ColumnConfig dataIndex="nextPhaseTransition" dateStyle="short" headerKey="phase_end" hideable="true" property="nextPhaseTransition" sortProperty="nextPhaseTransition" sortable="true" stateId="nextPhaseTransition" timeStyle="short"/>
            <ColumnConfig dataIndex="tags" headerKey="cert_tags" hideable="true" stateId="tags"/>
            <ColumnConfig dataIndex="creator" headerKey="requested_by" hideable="true" property="creator" sortProperty="creator" sortable="true" stateId="creator"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="create_date" hideable="true" property="created" sortProperty="created" sortable="true" stateId="created" timeStyle="none"/>
            <ColumnConfig dataIndex="expiration" dateStyle="short" headerKey="due" hideable="true" property="expiration" sortProperty="expiration" sortable="true" stateId="expiration" timeStyle="short"/>
            <ColumnConfig dataIndex="electronicallySigned" headerKey="electronically_signed" hidden="true" hideable="true" property="electronicallySigned" renderer="SailPoint.grid.Util.renderBoolean" sortProperty="electronicallySigned" sortable="true" stateId="electronicallySigned"/>
            <ColumnConfig dataIndex="totalEntites" fieldOnly="true" property="statistics.totalItems" sortProperty="statistics.totalItems" stateId="totalEntites"/>
            <ColumnConfig dataIndex="completedEntities" fieldOnly="true" property="statistics.completedItems" sortProperty="statistics.completedItems" stateId="completedEntities"/>
            <ColumnConfig dataIndex="percentComplete" fieldOnly="true" property="statistics.percentComplete" sortProperty="statistics.percentComplete" stateId="percentComplete"/>
            <ColumnConfig dataIndex="limitReassignments" fieldOnly="true" stateId="limitReassignments"/>
          </List>
        </value>
      </entry>
      <entry key="nameOnlyAccountGroupTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="displayableName" headerKey="name" hideable="true" property="displayableName" sortProperty="displayableName" sortable="true" stateId="displayableName" width="290"/>
            <ColumnConfig dataIndex="owner" headerKey="owner" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner" width="290"/>
          </List>
        </value>
      </entry>
      <entry key="policiesTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" percentWidth="25" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" percentWidth="15" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="description" headerKey="description" hideable="true" percentWidth="50" renderer="SailPoint.grid.Util.renderDescription" stateId="description"/>
            <ColumnConfig dataIndex="state" headerKey="state" hideable="true" percentWidth="10" property="state" sortProperty="state" sortable="true" stateId="state"/>
          </List>
        </value>
      </entry>
      <entry key="policyViolationStatusGridColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" headerKey="id" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="identity-name" headerKey="dash_policy_violation_col_identity" hideable="true" property="identity.name" secondarySort="id" sortProperty="identity.name" sortable="true" stateId="identity-name"/>
            <ColumnConfig dataIndex="policyName" headerKey="dash_policy_violation_col_policy" hideable="true" property="policyName" secondarySort="id" sortProperty="policyName" sortable="true" stateId="policyName"/>
            <ColumnConfig dataIndex="constraintName" headerKey="dash_policy_violation_col_constraint" hideable="true" property="constraintName" secondarySort="id" sortProperty="constraintName" sortable="true" stateId="constraintName"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="dash_policy_violation_col_detected" hideable="true" property="created" secondarySort="id" sortProperty="created" sortable="true" stateId="created"/>
          </List>
        </value>
      </entry>
      <entry key="policyViolationTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="identityName" headerKey="user" hideable="true" property="identityName" sortProperty="identity.name" sortable="true" stateId="identityName"/>
            <ColumnConfig dataIndex="identityFirstname" headerKey="firstName" hidden="true" hideable="true" property="identityFirstname" sortProperty="identity.firstname" sortable="true" stateId="identityFirstname"/>
            <ColumnConfig dataIndex="identityLastname" headerKey="lastName" hidden="true" hideable="true" property="identityLastname" sortProperty="identity.lastname" sortable="true" stateId="identityLastname"/>
            <ColumnConfig dataIndex="policyName" headerKey="policy" hideable="true" property="policyName" sortProperty="policyName" sortable="true" stateId="policyName"/>
            <ColumnConfig dataIndex="owner" headerKey="policy_violation_owner" hideable="true" localize="true" property="owner" sortProperty="owner.name" sortable="true" stateId="owner"/>
            <ColumnConfig dataIndex="constraint" headerKey="rule" hideable="true" property="constraint" sortProperty="constraintName" sortable="true" stateId="constraint"/>
            <ColumnConfig dataIndex="status" headerKey="status" hideable="true" localize="true" property="status" sortProperty="status" sortable="true" stateId="status"/>
            <ColumnConfig dataIndex="summary" headerKey="summary" hideable="true" noEscape="true" percentWidth="35" property="summary" sortProperty="description" sortable="true" stateId="summary"/>
          </List>
        </value>
      </entry>
      <entry key="populationEditTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="idents_grid_hdr_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="firstname" headerKey="idents_grid_hdr_first_name" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="idents_grid_hdr_last_name" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="manager-displayName" headerKey="idents_grid_hdr_manager" hideable="true" property="manager.displayName" sortProperty="manager.displayName" sortable="true" stateId="manager-displayName"/>
            <ColumnConfig dataIndex="lastRefresh" dateStyle="short" headerKey="idents_grid_hdr_last_refresh" hideable="true" property="lastRefresh" sortProperty="lastRefresh" sortable="true" stateId="lastRefresh"/>
          </List>
        </value>
      </entry>
      <entry key="populationTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" headerKey="description" hideable="true" percentWidth="45" property="description" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="visibility" headerKey="visibility" hideable="true" property="private" sortProperty="private" sortable="true" stateId="visibility"/>
            <ColumnConfig dataIndex="owner" headerKey="owner" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner"/>
            <ColumnConfig dataIndex="indexed" headerKey="enabled" hideable="true" property="indexed" sortProperty="indexed" sortable="true" stateId="indexed"/>
          </List>
        </value>
      </entry>
      <entry key="quicklinkPopulationQuicklinkListColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" flex="2.0" headerKey="label_name" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" flex="6.0" headerKey="label_description" localize="true" property="description" sortProperty="description" stateId="description"/>
            <ColumnConfig dataIndex="category" flex="1.0" headerKey="label_category" property="category" sortProperty="category" sortable="true" stateId="category"/>
            <ColumnConfig dataIndex="options" flex="1.0" headerKey="options" renderer="SailPoint.systemSetup.QuicklinkGrid.renderQuickLinkOptionsLink" stateId="options"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="action" fieldOnly="true" property="action" sortProperty="action" stateId="action"/>
          </List>
        </value>
      </entry>
      <entry key="requestsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="definition-name" headerKey="type" hideable="true" property="definition.name" sortProperty="definition.name" sortable="true" stateId="definition-name"/>
            <ColumnConfig dataIndex="string1" headerKey="target" hideable="true" property="string1" sortProperty="string1" sortable="true" stateId="string1"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="created" hideable="true" property="created" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="completed" dateStyle="short" headerKey="completed" hideable="true" property="completed" sortProperty="completed" sortable="true" stateId="completed"/>
            <ColumnConfig dataIndex="launched" dateStyle="short" headerKey="last_launch" hideable="true" property="launched" sortProperty="launched" sortable="true" stateId="launched"/>
            <ColumnConfig dataIndex="nextLaunch" dateStyle="short" headerKey="next_launch" hideable="true" property="nextLaunch" sortProperty="nextLaunch" sortable="true" stateId="nextLaunch"/>
            <ColumnConfig dataIndex="retryCount" headerKey="retry_count" hideable="true" property="retryCount" sortProperty="retryCount" sortable="true" stateId="retryCount"/>
          </List>
        </value>
      </entry>
      <entry key="riskScoreTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="firstname" headerKey="firstName" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="lastName" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="scorecard-compositeScore" headerKey="composite_score" hideable="true" property="scorecard.compositeScore" renderer="SailPoint.Manage.Grid.RiskScores.renderScore" sortProperty="scorecard.compositeScore" sortable="true" stateId="scorecard-compositeScore"/>
            <ColumnConfig dataIndex="scorecard-businessRoleScore" headerKey="business_role" hideable="true" property="scorecard.businessRoleScore" renderer="SailPoint.Manage.Grid.RiskScores.renderScore" sortProperty="scorecard.businessRoleScore" sortable="true" stateId="scorecard-businessRoleScore"/>
            <ColumnConfig dataIndex="scorecard-entitlementScore" headerKey="entitlement" hideable="true" property="scorecard.entitlementScore" renderer="SailPoint.Manage.Grid.RiskScores.renderScore" sortProperty="scorecard.entitlementScore" sortable="true" stateId="scorecard-entitlementScore"/>
            <ColumnConfig dataIndex="scorecard-policyScore" headerKey="policy" hideable="true" property="scorecard.policyScore" renderer="SailPoint.Manage.Grid.RiskScores.renderScore" sortProperty="scorecard.policyScore" sortable="true" stateId="scorecard-policyScore"/>
            <ColumnConfig dataIndex="scorecard-certificationScore" headerKey="certification" hideable="true" property="scorecard.certificationScore" renderer="SailPoint.Manage.Grid.RiskScores.renderScore" sortProperty="scorecard.certificationScore" sortable="true" stateId="scorecard-certificationScore"/>
          </List>
        </value>
      </entry>
      <entry key="roleExclusions">
        <value>
          <List>
            <ColumnConfig dataIndex="parent-targetName" headerKey="cert_exclusions_col_role" hideable="true" property="parent.targetName" sortProperty="parent.targetName" sortable="true" stateId="parent-targetName"/>
            <ColumnConfig dataIndex="type" headerKey="cert_exclusions_col_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="SPT_description" headerKey="cert_exclusions_col_desc" hideable="true" renderer="SailPoint.certification.ExclusionsGrid.renderDescription" sortProperty="SPT_description" sortable="true" stateId="SPT_description"/>
            <ColumnConfig dataIndex="parent-explanation" headerKey="cert_exclusions_col_reason" hideable="true" property="parent.explanation" sortProperty="parent.explanation" stateId="parent-explanation"/>
          </List>
        </value>
      </entry>
      <entry key="roleMetricsIdentitiesColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="displayName" headerKey="name" hideable="true" property="displayName" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="firstname" headerKey="firstName" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="lastName" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="name" hidden="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="manager-displayName" headerKey="manager" hideable="true" property="manager.displayName" sortProperty="manager.displayName" sortable="true" stateId="manager-displayName"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.LinkListBean">
        <value>
          <List>
            <ColumnConfig dataIndex="displayName" headerKey="link_account_id" hideable="true" property="displayName" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="application-name" headerKey="link_application" hideable="true" property="application.name" sortProperty="application.name" sortable="true" stateId="application-name"/>
            <ColumnConfig dataIndex="lastRefresh" dateStyle="short" headerKey="link_last_refresh" hideable="true" property="lastRefresh" sortProperty="lastRefresh" sortable="true" stateId="lastRefresh"/>
            <ColumnConfig dataIndex="nativeIdentity" fieldOnly="true" property="nativeIdentity" sortProperty="nativeIdentity" stateId="nativeIdentity"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.activity.ActivityCategoryList">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="Name" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="target" headerKey="Target" property="target" sortProperty="target" stateId="target"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AccessRequestBean">
        <value>
          <List>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="displayableName" headerKey="lcm_request_access_name" hideable="true" percentWidth="50" property="displayableName" renderer="SailPoint.LCM.RequestAccess.renderName" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="type" headerKey="lcm_request_access_type" hideable="true" percentWidth="10" property="type" renderer="SailPoint.LCM.RequestAccess.renderType" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="riskScore" headerKey="lcm_request_access_score" hideable="true" percentWidth="10" property="riskScore" renderer="SailPoint.LCM.RequestAccess.renderScore" sortProperty="riskScore" sortable="true" stateId="riskScore"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="lcm_request_access_owner" hideable="true" percentWidth="20" property="owner.displayName" renderer="SailPoint.LCM.RequestAccess.renderOwner" sortProperty="owner.displayName" sortable="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="IIQ_population" headerKey="lcm_role_population" hidden="true" hideable="true" percentWidth="10" renderer="SailPoint.LCM.RequestAccess.renderPopulation" stateId="IIQ_population"/>
            <ColumnConfig dataIndex="description" fieldOnly="true" property="description" sortProperty="description" stateId="description"/>
            <ColumnConfig dataIndex="application-name" fieldOnly="true" stateId="application-name"/>
            <ColumnConfig dataIndex="attribute" fieldOnly="true" stateId="attribute"/>
            <ColumnConfig dataIndex="displayableName" fieldOnly="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="IIQ_color" fieldOnly="true" stateId="IIQ_color"/>
            <ColumnConfig dataIndex="IIQ_icon" fieldOnly="true" stateId="IIQ_icon"/>
            <ColumnConfig dataIndex="IIQ_has_high_risk" fieldOnly="true" stateId="IIQ_has_high_risk"/>
            <ColumnConfig dataIndex="IIQ_population_total" fieldOnly="true" stateId="IIQ_population_total"/>
            <ColumnConfig dataIndex="owner-displayName" fieldOnly="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="IIQ_Selected" fieldOnly="true" stateId="IIQ_Selected"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AccessRequestBean_cart">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="" percentWidth="10" property="id" renderer="SailPoint.LCM.RequestAccess.buttonRenderer" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="displayableName" headerKey="lcm_summary_col_name" hideable="true" percentWidth="40" property="displayableName" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="type" headerKey="lcm_summary_col_type" hideable="true" percentWidth="30" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="action" headerKey="lcm_summary_col_action" hideable="true" percentWidth="20" property="action" renderer="SailPoint.LCM.SummaryChanges.actionRenderer" sortProperty="action" sortable="true" stateId="action"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AccessRequestBean_currently_assigned">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="" percentWidth="5" property="id" renderer="SailPoint.LCM.RequestAccess.currentAccessButtonRenderer" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="displayableName" headerKey="lcm_request_access_name" hideable="true" percentWidth="25" property="displayableName" renderer="SailPoint.LCM.RequestAccess.roleDetailRenderer" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="IIQ_status" headerKey="lcm_request_access_status" hideable="true" percentWidth="15" renderer="SailPoint.LCM.RequestAccess.statusRenderer" sortable="true" stateId="IIQ_status"/>
            <ColumnConfig dataIndex="IIQ_type" headerKey="lcm_request_access_type" hideable="true" percentWidth="20" sortable="true" stateId="IIQ_type"/>
            <ColumnConfig dataIndex="description" fieldOnly="true" property="description" sortProperty="description" stateId="description"/>
            <ColumnConfig dataIndex="IIQ_raw_type" fieldOnly="true" property="IIQ_raw_type" sortProperty="IIQ_raw_type" stateId="IIQ_raw_type"/>
            <ColumnConfig dataIndex="IIQ_Selected" fieldOnly="true" property="IIQ_Selected" sortProperty="IIQ_Selected" stateId="IIQ_Selected"/>
            <ColumnConfig dataIndex="application-name" headerKey="application" hideable="true" percentWidth="20" property="application" sortProperty="application" sortable="true" stateId="application-name"/>
            <ColumnConfig dataIndex="account" headerKey="account_name" hideable="true" percentWidth="20" property="account" sortProperty="account" sortable="true" stateId="account"/>
            <ColumnConfig dataIndex="nativeIdentity" headerKey="nativeIdentity" hidden="true" hideable="true" percentWidth="20" property="nativeIdentity" sortProperty="nativeIdentity" sortable="true" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="instance" headerKey="instance" hidden="true" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="attribute" fieldOnly="true" stateId="attribute"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="IIQ_status_class" fieldOnly="true" property="IIQ_status_class" sortProperty="IIQ_status_class" stateId="IIQ_status_class"/>
            <ColumnConfig dataIndex="assignmentId" fieldOnly="true" stateId="assignmentId"/>
            <ColumnConfig dataIndex="roleId" fieldOnly="true" stateId="roleId"/>
            <ColumnConfig dataIndex="removable" fieldOnly="true" stateId="removable"/>
            <ColumnConfig dataIndex="detectedOrAssigned" fieldOnly="true" stateId="detectedOrAssigned"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AccessRequestBean_summary">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="" percentWidth="3" property="id" renderer="SailPoint.LCM.SummaryChanges.buttonRenderer" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="value" headerKey="" percentWidth="7" property="value" renderer="SailPoint.LCM.SummaryChanges.editDetailsRenderer" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="action" headerKey="lcm_summary_col_action" hideable="true" percentWidth="8" property="action" renderer="SailPoint.LCM.SummaryChanges.actionRenderer" sortProperty="action" sortable="true" stateId="action"/>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="displayableName" headerKey="lcm_summary_col_name" hideable="true" percentWidth="35" property="displayableName" renderer="SailPoint.LCM.SummaryChanges.nameRenderer" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="type" headerKey="lcm_summary_col_type" hideable="true" percentWidth="10" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="assignmentNote" headerKey="lcm_summary_col_assignmentNote" hideable="true" percentWidth="15" property="assignmentNote" renderer="SailPoint.LCM.SummaryChanges.renderAssignmentNote" sortProperty="assignmentNote" stateId="assignmentNote"/>
            <ColumnConfig dataIndex="comments" headerKey="lcm_summary_col_comments" percentWidth="15" property="comments" renderer="SailPoint.LCM.SummaryChanges.renderComments" sortProperty="comments" stateId="comments"/>
            <ColumnConfig dataIndex="riskScore" headerKey="lcm_summary_col_risk_score" hideable="true" percentWidth="5" property="riskScore" renderer="SailPoint.LCM.SummaryChanges.renderScore" sortProperty="riskScore" sortable="true" stateId="riskScore"/>
            <ColumnConfig dataIndex="owner" headerKey="lcm_summary_col_owner" hideable="true" percentWidth="10" property="owner" sortProperty="owner" sortable="true" stateId="owner"/>
            <ColumnConfig dataIndex="IIQ_color" fieldOnly="true" stateId="IIQ_color"/>
            <ColumnConfig dataIndex="description" fieldOnly="true" property="description" sortProperty="description" stateId="description"/>
            <ColumnConfig dataIndex="attributes" fieldOnly="true" property="attributes" sortProperty="attributes" stateId="attributes"/>
            <ColumnConfig dataIndex="attribute" fieldOnly="true" property="attribute" sortProperty="attribute" stateId="attribute"/>
            <ColumnConfig dataIndex="application" fieldOnly="true" property="application" sortProperty="application" stateId="application"/>
            <ColumnConfig dataIndex="nativeIdentity" fieldOnly="true" property="nativeIdentity" sortProperty="nativeIdentity" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="updateable" fieldOnly="true" property="updateable" sortProperty="updateable" stateId="updateable"/>
            <ColumnConfig dataIndex="activation_pretty" fieldOnly="true" property="activation_pretty" sortProperty="activation_pretty" stateId="activation_pretty"/>
            <ColumnConfig dataIndex="activation" fieldOnly="true" property="activation" sortProperty="activation" stateId="activation"/>
            <ColumnConfig dataIndex="deactivation" fieldOnly="true" property="deactivation" sortProperty="deactivation" stateId="deactivation"/>
            <ColumnConfig dataIndex="deactivation_pretty" fieldOnly="true" property="deactivation_pretty" sortProperty="deactivation_pretty" stateId="deactivation_pretty"/>
            <ColumnConfig dataIndex="identityId" fieldOnly="true" property="identityId" sortProperty="identityId" stateId="identityId"/>
            <ColumnConfig dataIndex="objectId" fieldOnly="true" property="objectId" sortProperty="objectId" stateId="objectId"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AccountsRequestBean">
        <value>
          <List>
            <ColumnConfig dataIndex="id" property="id" renderer="SailPoint.LCM.ManageAccounts.buttonRenderer" sortProperty="id" stateId="id" width="30"/>
            <ColumnConfig dataIndex="displayName" headerKey="link_account_id" hideable="true" property="displayName" renderer="SailPoint.LCM.ManageAccounts.nameRenderer" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="IIQ_status" headerKey="lcm_manage_accounts_status" hideable="true" renderer="SailPoint.LCM.ManageAccounts.statusRenderer" sortable="true" stateId="IIQ_status" width="80"/>
            <ColumnConfig dataIndex="IIQ_status_class" fieldOnly="true" headerKey="lcm_manage_accounts_status_class" stateId="IIQ_status_class"/>
            <ColumnConfig dataIndex="application-name" headerKey="link_application" hideable="true" property="application.name" sortProperty="application.name" sortable="true" stateId="application-name"/>
            <ColumnConfig dataIndex="instance" headerKey="instance" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="lastRefresh" dateStyle="short" headerKey="link_last_refresh" hideable="true" property="lastRefresh" sortProperty="lastRefresh" sortable="true" stateId="lastRefresh"/>
            <ColumnConfig dataIndex="IIQ_refresh_status" headerKey="lcm_manage_accounts_refresh_status" renderer="SailPoint.LCM.ManageAccounts.refreshButtonRenderer" stateId="IIQ_refresh_status" width="140"/>
            <ColumnConfig dataIndex="nativeIdentity" fieldOnly="true" headerKey="native_identity" property="nativeIdentity" sortProperty="nativeIdentity" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="application-id" fieldOnly="true" headerKey="application" property="application.id" sortProperty="application.id" stateId="application-id"/>
            <ColumnConfig dataIndex="IIQ_decisions" fieldOnly="true" headerKey="IIQ_decisions" stateId="IIQ_decisions"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AccountsRequestBean_cart">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="" percentWidth="10" property="id" renderer="SailPoint.LCM.RequestAccess.buttonRenderer" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="account" headerKey="lcm_summary_account" hideable="true" percentWidth="40" property="account" sortProperty="account" sortable="true" stateId="account"/>
            <ColumnConfig dataIndex="application" headerKey="lcm_summary_application" hideable="true" percentWidth="30" property="application" sortProperty="application" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="op" headerKey="lcm_summary_action" hideable="true" percentWidth="20" property="op" renderer="SailPoint.LCM.SummaryChanges.actionRenderer" sortProperty="op" sortable="true" stateId="op"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AccountsRequestBean_summary">
        <value>
          <List>
            <ColumnConfig dataIndex="id" property="id" renderer="SailPoint.LCM.SummaryChanges.buttonRenderer" sortProperty="id" stateId="id" width="33"/>
            <ColumnConfig dataIndex="opName" headerKey="lcm_summary_action" hideable="true" property="opName" renderer="SailPoint.LCM.SummaryChanges.renderAction" sortProperty="opName" sortable="true" stateId="opName"/>
            <ColumnConfig dataIndex="op" fieldOnly="true" headerKey="lcm_summary_action" property="op" sortProperty="op" stateId="op"/>
            <ColumnConfig dataIndex="identity" flex="1.0" headerKey="lcm_summary_identity" hideable="true" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
            <ColumnConfig dataIndex="applicationName" flex="1.0" headerKey="lcm_summary_application" hideable="true" property="applicationName" sortProperty="applicationName" sortable="true" stateId="applicationName"/>
            <ColumnConfig dataIndex="instance" headerKey="lcm_summary_instance" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="account" headerKey="lcm_summary_account" hideable="true" property="account" renderer="SailPoint.LCM.SummaryChanges.renderAccount" sortProperty="account" sortable="true" stateId="account"/>
            <ColumnConfig dataIndex="application" fieldOnly="true" headerKey="applicationId" hideable="true" property="application" sortProperty="application" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="nativeIdentity" fieldOnly="true" headerKey="native_identity" hideable="true" property="nativeIdentity" sortProperty="nativeIdentity" sortable="true" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="comments" headerKey="lcm_request_comments" property="comments" renderer="SailPoint.LCM.SummaryChanges.renderComments" sortProperty="comments" stateId="comments"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AttributesRequestBean_cart">
        <value>
          <List>
            <ColumnConfig dataIndex="id" percentWidth="10" property="id" renderer="SailPoint.LCM.RequestAccess.buttonRenderer" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="opName" headerKey="lcm_summary_action" hideable="true" percentWidth="20" property="opName" renderer="SailPoint.LCM.SummaryChanges.renderAction" sortProperty="opName" sortable="true" stateId="opName"/>
            <ColumnConfig dataIndex="op" fieldOnly="true" headerKey="lcm_summary_action" percentWidth="20" property="op" sortProperty="op" stateId="op"/>
            <ColumnConfig dataIndex="summary" headerKey="lcm_summary_summary" hideable="true" percentWidth="30" property="summary" renderer="Ext.util.Format.defaultValue" sortProperty="summary" sortable="true" stateId="summary"/>
            <ColumnConfig dataIndex="identity" headerKey="lcm_summary_identity" hideable="true" percentWidth="20" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.AttributesRequestBean_summary">
        <value>
          <List>
            <ColumnConfig dataIndex="id" property="id" renderer="SailPoint.LCM.SummaryChanges.buttonRenderer" sortProperty="id" stateId="id" width="33"/>
            <ColumnConfig dataIndex="opName" headerKey="lcm_summary_action" hideable="true" property="opName" renderer="SailPoint.LCM.SummaryChanges.renderAction" sortProperty="opName" sortable="true" stateId="opName"/>
            <ColumnConfig dataIndex="op" fieldOnly="true" headerKey="lcm_summary_action" property="op" sortProperty="op" stateId="op"/>
            <ColumnConfig dataIndex="summary" headerKey="lcm_summary_summary" hideable="true" property="summary" renderer="Ext.util.Format.defaultValue" sortProperty="summary" sortable="true" stateId="summary"/>
            <ColumnConfig dataIndex="identity" headerKey="lcm_summary_identity" hideable="true" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.EntitlementsRequestBean">
        <value>
          <List>
            <ColumnConfig dataIndex="id" property="id" renderer="SailPoint.LCM.CurrentEntitlementsGrid.buttonRenderer" sortProperty="id" stateId="id" width="5"/>
            <ColumnConfig dataIndex="application" headerKey="lcm_request_entitlements_application" hideable="true" property="application" sortProperty="application" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="instance" headerKey="lcm_request_entitlements_instance" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="displayName" headerKey="lcm_request_entitlements_native_identity" hideable="true" property="displayName" renderer="SailPoint.LCM.CurrentEntitlementsGrid.displayNameRenderer" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="attribute" headerKey="lcm_request_entitlements_attribute" hideable="true" property="attribute" renderer="SailPoint.LCM.CurrentEntitlementsGrid.attributeRenderer" sortProperty="attribute" sortable="true" stateId="attribute"/>
            <ColumnConfig dataIndex="displayValue" headerKey="lcm_request_entitlements_value" hideable="true" property="displayValue" renderer="SailPoint.LCM.CurrentEntitlementsGrid.displayValueRenderer" sortProperty="displayValue" sortable="true" stateId="displayValue"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="nativeIdentity" fieldOnly="true" property="nativeIdentity" sortProperty="nativeIdentity" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="description" fieldOnly="true" property="description" sortProperty="description" stateId="description"/>
            <ColumnConfig dataIndex="showDescriptionFirst" fieldOnly="true" property="showDescriptionFirst" sortProperty="showDescriptionFirst" stateId="showDescriptionFirst"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.EntitlementsRequestBean_search">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="application-id" fieldOnly="true" property="application.id" sortProperty="application.id" stateId="application-id"/>
            <ColumnConfig dataIndex="application-icon" fieldOnly="true" property="application.icon" sortProperty="application.icon" stateId="application-icon"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="IIQ_has_high_risk" fieldOnly="true" stateId="IIQ_has_high_risk"/>
            <ColumnConfig dataIndex="IIQ_allow_slider" fieldOnly="true" stateId="IIQ_allow_slider"/>
            <ColumnConfig dataIndex="IIQ_population_total" fieldOnly="true" stateId="IIQ_population_total"/>
            <ColumnConfig dataIndex="application-name" headerKey="lcm_request_entitlements_application" hideable="true" property="application.name" secondarySort="attribute, displayableName" sortProperty="application.name" sortable="true" stateId="application-name"/>
            <ColumnConfig dataIndex="attribute" headerKey="lcm_request_entitlements_attribute" hideable="true" property="attribute" secondarySort="application.name, displayableName" sortProperty="attribute" sortable="true" stateId="attribute"/>
            <ColumnConfig dataIndex="displayableName" headerKey="lcm_request_entitlements_entitlement" hideable="true" property="displayableName" secondarySort="application.name, attribute" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="description" headerKey="lcm_request_entitlements_description" hideable="true" percentWidth="40" stateId="description"/>
            <ColumnConfig dataIndex="IIQ_population" fieldOnly="true" headerKey="lcm_role_population" hideable="true" stateId="IIQ_population"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="lcm_request_entitlements_owner" hideable="true" property="owner.displayName" secondarySort="application.name, attribute, displayableName" sortProperty="owner.displayName" sortable="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="riskScore" headerKey="lcm_request_entitlements_risk" hideable="true" renderer="SailPoint.LCM.RequestAccess.riskScoreRenderer" stateId="riskScore"/>
            <ColumnConfig dataIndex="IIQ_color" fieldOnly="true" stateId="IIQ_color"/>
            <ColumnConfig dataIndex="owner-name" fieldOnly="true" property="owner.name" sortProperty="owner.name" stateId="owner-name"/>
            <ColumnConfig dataIndex="IIQ_icon" fieldOnly="true" stateId="IIQ_icon"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.PasswordsRequestBean">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="displayName" headerKey="link_account_id" hideable="true" property="displayName" renderer="SailPoint.LCM.AccountsGridSupport.nameRenderer" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="application-name" headerKey="link_application" hideable="true" property="application.name" renderer="SailPoint.LCM.ManagePasswords.linkPasswordPolicyRenderer" sortProperty="application.name" sortable="true" stateId="application-name"/>
            <ColumnConfig dataIndex="instance" headerKey="instance" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="IIQ_status" headerKey="lcm_manage_accounts_status" hideable="true" renderer="SailPoint.LCM.AccountsGridSupport.statusRenderer" sortable="true" stateId="IIQ_status" width="100"/>
            <ColumnConfig dataIndex="IIQ_status_class" fieldOnly="true" stateId="IIQ_status_class"/>
            <ColumnConfig dataIndex="nativeIdentity" fieldOnly="true" property="nativeIdentity" sortProperty="nativeIdentity" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="application-id" fieldOnly="true" property="application.id" sortProperty="application.id" stateId="application-id"/>
            <ColumnConfig dataIndex="password_requirements" fieldOnly="true" stateId="password_requirements"/>
            <ColumnConfig dataIndex="supports_current_password" fieldOnly="true" stateId="supports_current_password"/>
            <ColumnConfig dataIndex="lastRefresh" dateStyle="short" headerKey="link_last_refresh" hideable="true" property="lastRefresh" sortProperty="lastRefresh" sortable="true" stateId="lastRefresh"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.PasswordsRequestBean_cart">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="" percentWidth="10" property="id" renderer="SailPoint.LCM.RequestAccess.buttonRenderer" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="identity" headerKey="lcm_summary_identity" hideable="true" percentWidth="30" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
            <ColumnConfig dataIndex="application" headerKey="lcm_summary_application" hideable="true" percentWidth="20" property="application" sortProperty="application" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="account" headerKey="lcm_summary_account" hideable="true" percentWidth="20" property="account" sortProperty="account" sortable="true" stateId="account"/>
            <ColumnConfig dataIndex="value" headerKey="lcm_summary_password" hideable="true" percentWidth="20" property="value" sortProperty="value" sortable="true" stateId="value"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.PasswordsRequestBean_summary">
        <value>
          <List>
            <ColumnConfig dataIndex="id" headerKey="" property="id" renderer="SailPoint.LCM.SummaryChanges.buttonRenderer" sortProperty="id" stateId="id" width="30"/>
            <ColumnConfig dataIndex="identity" headerKey="lcm_summary_identity" hideable="true" property="identity" sortProperty="identity" sortable="true" stateId="identity"/>
            <ColumnConfig dataIndex="application" headerKey="lcm_summary_application" hideable="true" property="application" sortProperty="application" sortable="true" stateId="application"/>
            <ColumnConfig dataIndex="instance" headerKey="lcm_summary_instance" hideable="true" property="instance" sortProperty="instance" sortable="true" stateId="instance"/>
            <ColumnConfig dataIndex="account" headerKey="lcm_summary_account" hideable="true" property="account" sortProperty="account" sortable="true" stateId="account"/>
            <ColumnConfig dataIndex="value" headerKey="lcm_summary_password" hideable="true" property="value" renderer="SailPoint.LCM.SummaryChanges.renderPassword" sortProperty="value" sortable="true" stateId="value"/>
            <ColumnConfig dataIndex="comments" flex="1.0" headerKey="lcm_request_comments" property="comments" renderer="SailPoint.LCM.SummaryChanges.renderComments" sortProperty="comments" stateId="comments"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.RequestPopulationBean">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="IIQ_Selected" fieldOnly="true" stateId="IIQ_Selected"/>
            <ColumnConfig dataIndex="name" flex="1.0" headerKey="idents_grid_hdr_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="firstname" flex="1.0" headerKey="idents_grid_hdr_first_name" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" flex="1.0" headerKey="idents_grid_hdr_last_name" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="manager-displayName" flex="1.0" headerKey="idents_grid_hdr_manager" hideable="true" property="manager.displayName" sortProperty="manager.displayName" sortable="true" stateId="manager-displayName"/>
            <ColumnConfig dataIndex="displayName" fieldOnly="true" flex="1.0" headerKey="idents_grid_hdr_display_name" property="displayName" sortProperty="displayName" stateId="displayName"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.RolesRequestBean">
        <value>
          <List>
            <ColumnConfig dataIndex="id" property="id" renderer="SailPoint.LCM.RequestAccess.buttonRenderer" sortProperty="id" stateId="id" width="5"/>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="displayableName" headerKey="lcm_role_name" hideable="true" property="displayableName" sortProperty="displayableName" sortable="true" stateId="displayableName" width="40"/>
            <ColumnConfig dataIndex="description" headerKey="lcm_role_description" hideable="true" property="description" renderer="SailPoint.LCM.RequestAccess.descriptionRenderer" sortProperty="description" stateId="description"/>
            <ColumnConfig dataIndex="IIQ_authorization" headerKey="lcm_role_authorization" hideable="true" stateId="IIQ_authorization" width="40"/>
            <ColumnConfig dataIndex="IIQ_status" headerKey="lcm_role_status" hideable="true" renderer="SailPoint.LCM.RequestAccess.statusRenderer" sortable="true" stateId="IIQ_status" width="30"/>
            <ColumnConfig dataIndex="IIQ_status_class" fieldOnly="true" headerKey="lcm_role_status_class" stateId="IIQ_status_class"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" headerKey="lcm_role_type_hidden" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="roleTypeName" headerKey="lcm_role_type" hideable="true" property="type" renderer="SailPoint.LCM.RequestAccess.typeRenderer" sortProperty="type" sortable="true" stateId="roleTypeName" width="30"/>
            <ColumnConfig dataIndex="roleTypeIcon" fieldOnly="true" headerKey="lcm_role_type_icon" stateId="roleTypeIcon"/>
            <ColumnConfig dataIndex="riskScoreWeight" headerKey="idents_grid_hdr_composite_score" hideable="true" property="riskScoreWeight" renderer="SailPoint.LCM.RequestAccess.scoreRenderer" sortProperty="riskScoreWeight" sortable="true" stateId="riskScoreWeight" width="20"/>
            <ColumnConfig dataIndex="IIQ_color" fieldOnly="true" stateId="IIQ_color"/>
            <ColumnConfig dataIndex="owner-displayName" fieldOnly="true" property="owner.displayName" sortProperty="owner.displayName" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="IIQ_Selected" fieldOnly="true" stateId="IIQ_Selected"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.lcm.RolesRequestBean_search">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="displayableName" flex="1.0" headerKey="lcm_role_name" hideable="true" property="displayableName" sortProperty="displayableName" sortable="true" stateId="displayableName"/>
            <ColumnConfig dataIndex="typeName" headerKey="lcm_role_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="typeName"/>
            <ColumnConfig dataIndex="IIQ_population" fieldOnly="true" headerKey="lcm_role_population" stateId="IIQ_population"/>
            <ColumnConfig dataIndex="IIQ_has_high_risk" fieldOnly="true" headerKey="lcm_role_type_high_risk" stateId="IIQ_has_high_risk"/>
            <ColumnConfig dataIndex="roleTypeIcon" fieldOnly="true" headerKey="lcm_role_type_icon" stateId="roleTypeIcon"/>
            <ColumnConfig dataIndex="IIQ_population_total" fieldOnly="true" headerKey="lcm_role_population_total" stateId="IIQ_population_total"/>
            <ColumnConfig dataIndex="IIQ_allow_slider" fieldOnly="true" headerKey="lcm_role_allow_slider" stateId="IIQ_allow_slider"/>
            <ColumnConfig dataIndex="riskScore" headerKey="idents_grid_hdr_composite_score" hideable="true" property="riskScoreWeight" renderer="SailPoint.LCM.RequestAccess.riskScoreRenderer" sortProperty="riskScoreWeight" sortable="true" stateId="riskScore"/>
            <ColumnConfig dataIndex="IIQ_color" fieldOnly="true" stateId="IIQ_color"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="owner" property="owner.displayName" sortProperty="owner.displayName" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="IIQ_icon" fieldOnly="true" stateId="IIQ_icon"/>
            <ColumnConfig dataIndex="IIQ_Selected" fieldOnly="true" stateId="IIQ_Selected"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.mining.ITRoleMiningPopulationBean">
        <value>
          <List>
            <ColumnConfig dataIndex="displayName" headerKey="name" hideable="true" property="displayName" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="firstname" headerKey="firstName" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="lastName" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="manager-displayName" headerKey="manager" hideable="true" property="manager.displayName" sortProperty="manager.displayName" sortable="true" stateId="manager-displayName"/>
          </List>
        </value>
      </entry>
      <entry key="sailpoint.web.trigger.IdentityTriggersListBean">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="identity_trigger_tbl_header_name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="type" headerKey="identity_trigger_tbl_header_type" hideable="true" property="type" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="attributeName" headerKey="identity_trigger_tbl_header_attribute_name" hideable="true" property="attributeName" sortProperty="attributeName" sortable="true" stateId="attributeName"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="identity_trigger_tbl_header_owner" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="disabled" headerKey="identity_trigger_tbl_header_disabled" hideable="true" property="disabled" renderer="SailPoint.Define.Trigger.Triggers.renderDisabled" sortProperty="disabled" sortable="true" stateId="disabled"/>
          </List>
        </value>
      </entry>
      <entry key="subGroupDefinitionTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="memberCount" headerKey="member_count" hideable="true" property="index.memberCount" sortProperty="index.memberCount" sortable="true" stateId="memberCount"/>
            <ColumnConfig dataIndex="totalViolations" headerKey="title_policy_violations" hideable="true" property="index.totalViolations" sortProperty="index.totalViolations" sortable="true" stateId="totalViolations"/>
            <ColumnConfig dataIndex="compositeScore" headerKey="composite_score" hideable="true" property="index.compositeScore" renderer="renderScore" sortProperty="index.compositeScore" sortable="true" stateId="compositeScore"/>
            <ColumnConfig dataIndex="owner" headerKey="owner" hideable="true" property="owner.displayName" sortProperty="owner.displayName" sortable="true" stateId="owner"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="last_updated" hideable="true" property="index.created" sortProperty="index.created" sortable="true" stateId="modified"/>
          </List>
        </value>
      </entry>
      <entry key="taskDefinitionTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" flex="1.0" headerKey="name" hideable="true" property="name" renderer="htmlEncode" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" flex="2.0" headerKey="description" hideable="true" property="description" renderer="htmlEncode" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="subtype" headerKey="category" hidden="true" hideable="true" property="subtype" sortProperty="subtype" stateId="subtype"/>
            <ColumnConfig dataIndex="type" headerKey="type" hidden="true" hideable="true" stateId="type"/>
            <ColumnConfig dataIndex="progressMode" fieldOnly="true" stateId="progressMode"/>
          </List>
        </value>
      </entry>
      <entry key="taskResultsTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="completed" headerKey="date_complete" hideable="true" property="completed" secondarySort="id" sortProperty="completed" sortable="true" stateId="completed"/>
            <ColumnConfig dataIndex="completionStatus" headerKey="result" hideable="true" property="completionStatus" renderer="renderStatus" secondarySort="id" sortProperty="completionStatus" sortable="true" stateId="completionStatus"/>
            <ColumnConfig dataIndex="pendingSignoffs" headerKey="signoff" hideable="true" property="pendingSignoffs" sortProperty="pendingSignoffs" stateId="pendingSignoffs"/>
            <ColumnConfig dataIndex="owner-displayName" headerKey="owner" hideable="true" property="owner.displayName" secondarySort="id" sortProperty="owner.displayName" sortable="true" stateId="owner-displayName"/>
            <ColumnConfig dataIndex="statusId" fieldOnly="true" stateId="statusId"/>
            <ColumnConfig dataIndex="subtype" fieldOnly="true" stateId="subtype"/>
          </List>
        </value>
      </entry>
      <entry key="taskScheduleTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" flex="1.0" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="definition-name" headerKey="task" hideable="true" property="definition.name" sortProperty="definition.name" sortable="true" stateId="definition-name"/>
            <ColumnConfig dataIndex="nextExecution" headerKey="next_execution" hideable="true" property="nextExecution" sortProperty="nextExecution" sortable="true" stateId="nextExecution"/>
            <ColumnConfig dataIndex="lastExecution" headerKey="last_execution" hideable="true" property="lastExecution" sortProperty="lastExecution" sortable="true" stateId="lastExecution"/>
            <ColumnConfig dataIndex="latestResult" headerKey="result" hideable="true" property="latestResult" renderer="renderStatus" sortProperty="latestResult" sortable="true" stateId="latestResult"/>
            <ColumnConfig dataIndex="launcher" headerKey="owner" hideable="true" property="launcher" sortProperty="launcher" sortable="true" stateId="launcher"/>
            <ColumnConfig dataIndex="statusId" fieldOnly="true" property="statusId" sortProperty="statusId" stateId="statusId"/>
            <ColumnConfig dataIndex="latestResultId" fieldOnly="true" stateId="latestResultId"/>
            <ColumnConfig dataIndex="subtype" fieldOnly="true" stateId="subtype"/>
          </List>
        </value>
      </entry>
      <entry key="uiAccessItemsColumnsEntitlement">
        <value>
          <List>
            <ColumnConfig dataIndex="displayableAccessType" headerKey="ui_access_type" stateId="displayableAccessType"/>
            <ColumnConfig dataIndex="owner" headerKey="ui_access_owner" property="owner.displayName" sortProperty="owner.displayName" stateId="owner"/>
            <ColumnConfig dataIndex="application" headerKey="ui_access_application" property="application.name" sortProperty="application.name" stateId="application"/>
            <ColumnConfig dataIndex="attribute" headerKey="ui_access_attribute" property="attribute" sortProperty="attribute" stateId="attribute"/>
            <ColumnConfig dataIndex="accountName" headerKey="ui_access_account" stateId="accountName"/>
            <ColumnConfig dataIndex="populationStatistics" fieldOnly="true" stateId="populationStatistics"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="displayableName" fieldOnly="true" property="displayableName" sortProperty="displayableName" stateId="displayableName"/>
            <ColumnConfig dataIndex="icon" fieldOnly="true" property="application.icon" sortProperty="application.icon" stateId="icon"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
          </List>
        </value>
      </entry>
      <entry key="uiAccessItemsColumnsRole">
        <value>
          <List>
            <ColumnConfig dataIndex="displayableAccessType" headerKey="ui_access_type" stateId="displayableAccessType"/>
            <ColumnConfig dataIndex="owner" headerKey="ui_access_owner" property="owner.displayName" sortProperty="owner.displayName" stateId="owner"/>
            <ColumnConfig dataIndex="riskScoreWeight" headerKey="ui_access_risk" property="riskScoreWeight" renderer="risk" sortProperty="riskScoreWeight" stateId="riskScoreWeight"/>
            <ColumnConfig dataIndex="populationStatistics" fieldOnly="true" stateId="populationStatistics"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="displayableName" fieldOnly="true" property="displayableName" sortProperty="displayableName" stateId="displayableName"/>
            <ColumnConfig dataIndex="riskScoreColor" fieldOnly="true" stateId="riskScoreColor"/>
            <ColumnConfig dataIndex="riskScoreTextColor" fieldOnly="true" stateId="riskScoreTextColor"/>
          </List>
        </value>
      </entry>
      <entry key="uiAccessRequestItemPopulationColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" headerKey="ui_idents_grid_hdr_name" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="firstname" headerKey="ui_idents_grid_hdr_first_name" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="ui_idents_grid_hdr_last_name" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
            <ColumnConfig dataIndex="manager" headerKey="ui_idents_grid_hdr_manager" property="manager.displayName" sortProperty="manager.displayName" sortable="true" stateId="manager"/>
            <ColumnConfig dataIndex="score" headerKey="ui_idents_grid_hdr_composite_score" property="scorecard.compositeScore" renderer="risk" sortProperty="scorecard.compositeScore" sortable="true" stateId="score"/>
            <ColumnConfig dataIndex="violations" headerKey="ui_idents_grid_hdr_policy_violations" property="scorecard.totalViolations" sortProperty="scorecard.totalViolations" sortable="true" stateId="violations"/>
          </List>
        </value>
      </entry>
      <entry key="uiApprovalItemsColumnsEntitlement">
        <value>
          <List>
            <ColumnConfig dataIndex="operation" headerKey="my_approvals_action_col" renderer="operation" stateId="operation"/>
            <ColumnConfig dataIndex="application" headerKey="my_approvals_application_col" property="application" sortProperty="application" stateId="application"/>
            <ColumnConfig dataIndex="name" headerKey="my_approvals_attribute_col" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="sunriseSunset" headerKey="my_approvals_dates_col" renderer="sunriseSunset" stateId="sunriseSunset"/>
            <ColumnConfig dataIndex="isNewAccount" fieldOnly="true" stateId="isNewAccount"/>
            <ColumnConfig dataIndex="sunrise" fieldOnly="true" stateId="sunrise"/>
            <ColumnConfig dataIndex="sunset" fieldOnly="true" stateId="sunset"/>
            <ColumnConfig dataIndex="hadSunriseSunset" fieldOnly="true" stateId="hadSunriseSunset"/>
          </List>
        </value>
      </entry>
      <entry key="uiApprovalItemsColumnsRole">
        <value>
          <List>
            <ColumnConfig dataIndex="operation" headerKey="my_approvals_action_col" renderer="operation" stateId="operation"/>
            <ColumnConfig dataIndex="riskScoreWeight" headerKey="my_approvals_risk_col" renderer="risk" stateId="riskScoreWeight"/>
            <ColumnConfig dataIndex="sunriseSunset" headerKey="my_approvals_dates_col" renderer="sunriseSunset" stateId="sunriseSunset"/>
            <ColumnConfig dataIndex="isNewAccount" fieldOnly="true" stateId="isNewAccount"/>
            <ColumnConfig dataIndex="sunrise" fieldOnly="true" stateId="sunrise"/>
            <ColumnConfig dataIndex="sunset" fieldOnly="true" stateId="sunset"/>
            <ColumnConfig dataIndex="hadSunriseSunset" fieldOnly="true" stateId="hadSunriseSunset"/>
          </List>
        </value>
      </entry>
      <entry key="uiApprovalsListColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="id" property="id" sortProperty="id" sortable="true" stateId="id"/>
            <ColumnConfig dataIndex="created" property="created" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="priority" property="level" sortProperty="level" sortable="true" stateId="priority"/>
            <ColumnConfig dataIndex="requestType" property="IdentityRequest.type" sortProperty="IdentityRequest.type" stateId="requestType"/>
            <ColumnConfig dataIndex="requester" property="requester" sortProperty="requester" stateId="requester"/>
            <ColumnConfig dataIndex="owner" property="owner" sortProperty="owner" stateId="owner"/>
            <ColumnConfig dataIndex="workItemName" property="name" sortProperty="name" stateId="workItemName"/>
            <ColumnConfig dataIndex="accessRequestName" property="IdentityRequest.name" sortProperty="IdentityRequest.name" stateId="accessRequestName"/>
            <ColumnConfig dataIndex="assignee" property="assignee" sortProperty="assignee" stateId="assignee"/>
            <ColumnConfig dataIndex="approvalItems" stateId="approvalItems"/>
            <ColumnConfig dataIndex="target" stateId="target"/>
            <ColumnConfig dataIndex="esigMeaning" stateId="esigMeaning"/>
            <ColumnConfig dataIndex="violations" stateId="violations"/>
            <ColumnConfig dataIndex="commentCount" stateId="commentCount"/>
          </List>
        </value>
      </entry>
      <entry key="uiApprovalsWidgetColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="target" headerKey="ui_work_items_widget_approval_for" renderer="targetOrDescription,priorityFlag" stateId="target"/>
            <ColumnConfig dataIndex="requester" headerKey="ui_work_items_widget_requester" renderer="displayableName" stateId="requester"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="ui_work_items_widget_date" property="created" sortProperty="created" stateId="created"/>
          </List>
        </value>
      </entry>
      <entry key="uiCurrentAccessItemsColumnsEntitlement">
        <value>
          <List>
            <ColumnConfig dataIndex="displayableAccessType" headerKey="ui_access_type" stateId="displayableAccessType"/>
            <ColumnConfig dataIndex="owner" headerKey="ui_access_owner" property="owner.displayName" sortProperty="owner.displayName" stateId="owner"/>
            <ColumnConfig dataIndex="application" headerKey="ui_access_application" property="application.name" sortProperty="application.name" stateId="application"/>
            <ColumnConfig dataIndex="attribute" headerKey="ui_access_attribute" property="attribute" sortProperty="attribute" stateId="attribute"/>
            <ColumnConfig dataIndex="instance" headerKey="ui_access_instance" stateId="instance"/>
            <ColumnConfig dataIndex="accountName" headerKey="ui_access_account" stateId="accountName"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="displayableName" fieldOnly="true" property="displayableName" sortProperty="displayableName" stateId="displayableName"/>
            <ColumnConfig dataIndex="icon" fieldOnly="true" property="application.icon" sortProperty="application.icon" stateId="icon"/>
            <ColumnConfig dataIndex="value" fieldOnly="true" property="value" sortProperty="value" stateId="value"/>
            <ColumnConfig dataIndex="nativeIdentity" fieldOnly="true" stateId="nativeIdentity"/>
            <ColumnConfig dataIndex="sunrise" fieldOnly="true" stateId="sunrise"/>
            <ColumnConfig dataIndex="sunset" fieldOnly="true" stateId="sunset"/>
            <ColumnConfig dataIndex="status" fieldOnly="true" stateId="status"/>
            <ColumnConfig dataIndex="removable" fieldOnly="true" stateId="removable"/>
          </List>
        </value>
      </entry>
      <entry key="uiCurrentAccessItemsColumnsRole">
        <value>
          <List>
            <ColumnConfig dataIndex="displayableAccessType" headerKey="ui_access_type" stateId="displayableAccessType"/>
            <ColumnConfig dataIndex="owner" headerKey="ui_access_owner" property="owner.displayName" sortProperty="owner.displayName" stateId="owner"/>
            <ColumnConfig dataIndex="riskScoreWeight" headerKey="ui_access_risk" property="riskScoreWeight" renderer="risk" sortProperty="riskScoreWeight" stateId="riskScoreWeight"/>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="name" fieldOnly="true" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="type" fieldOnly="true" property="type" sortProperty="type" stateId="type"/>
            <ColumnConfig dataIndex="displayableName" fieldOnly="true" property="displayableName" sortProperty="displayableName" stateId="displayableName"/>
            <ColumnConfig dataIndex="riskScoreColor" fieldOnly="true" stateId="riskScoreColor"/>
            <ColumnConfig dataIndex="riskScoreTextColor" fieldOnly="true" stateId="riskScoreTextColor"/>
            <ColumnConfig dataIndex="sunrise" fieldOnly="true" stateId="sunrise"/>
            <ColumnConfig dataIndex="sunset" fieldOnly="true" stateId="sunset"/>
            <ColumnConfig dataIndex="status" fieldOnly="true" stateId="status"/>
            <ColumnConfig dataIndex="roleTargets" fieldOnly="true" stateId="roleTargets"/>
            <ColumnConfig dataIndex="assignmentId" fieldOnly="true" stateId="assignmentId"/>
            <ColumnConfig dataIndex="assignmentNote" fieldOnly="true" stateId="assignmentNote"/>
            <ColumnConfig dataIndex="removable" fieldOnly="true" stateId="removable"/>
          </List>
        </value>
      </entry>
      <entry key="uiFormsWidgetColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="description" headerKey="ui_work_items_widget_name" renderer="priorityFlag" stateId="description"/>
            <ColumnConfig dataIndex="requester" headerKey="ui_work_items_widget_requester" renderer="displayableName" stateId="requester"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="ui_work_items_widget_date" property="created" sortProperty="created" stateId="created"/>
          </List>
        </value>
      </entry>
      <entry key="uiRequestAccessIdentityCard">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="displayName" fieldOnly="true" property="displayName" sortProperty="displayName" sortable="true" stateId="displayName"/>
            <ColumnConfig dataIndex="name" headerKey="ui_access_username" property="name" sortProperty="name" stateId="name"/>
            <ColumnConfig dataIndex="managerName" headerKey="ui_access_manager" property="manager.displayName" sortProperty="manager.displayName" stateId="managerName"/>
          </List>
        </value>
      </entry>
      <entry key="uiViolationReviewRequestedEntitlement">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="entitlementApplication" headerKey="ui_violation_review_col_application" property="applicationName" sortProperty="applicationName" stateId="entitlementApplication"/>
            <ColumnConfig dataIndex="entitlementName" headerKey="ui_violation_review_col_entitlement_name" property="displayName" sortProperty="displayName" stateId="entitlementName"/>
            <ColumnConfig dataIndex="entitlementValue" headerKey="ui_violation_review_col_entitlement_value" property="displayableValue" sortProperty="displayableValue" stateId="entitlementValue"/>
            <ColumnConfig dataIndex="accountName" headerKey="ui_violation_review_col_account_name" property="accountDisplayName" sortProperty="accountDisplayName" stateId="accountName"/>
          </List>
        </value>
      </entry>
      <entry key="uiViolationReviewRequestedRole">
        <value>
          <List>
            <ColumnConfig dataIndex="id" fieldOnly="true" property="id" sortProperty="id" stateId="id"/>
            <ColumnConfig dataIndex="roleName" headerKey="ui_violation_review_col_role_name" property="role" sortProperty="role" stateId="roleName"/>
          </List>
        </value>
      </entry>
      <entry key="uiViolationsWidgetColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="description" headerKey="ui_work_items_widget_name" renderer="priorityFlag" stateId="description"/>
            <ColumnConfig dataIndex="target" headerKey="ui_work_items_widget_user" renderer="displayableName" stateId="target"/>
            <ColumnConfig dataIndex="created" dateStyle="short" headerKey="ui_work_items_widget_date" property="created" sortProperty="created" stateId="created"/>
          </List>
        </value>
      </entry>
      <entry key="workItemViolationTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="workitemId" fieldOnly="true" property="workitemId" sortProperty="workitemId" stateId="workitemId"/>
            <ColumnConfig dataIndex="policyOwner" fieldOnly="true" property="policyOwner" sortProperty="policyOwner" stateId="policyOwner"/>
            <ColumnConfig dataIndex="policyName" headerKey="impact_column_policy" percentWidth="15" property="policyName" sortProperty="policyName" stateId="policyName"/>
            <ColumnConfig dataIndex="ruleName" headerKey="impact_column_constraint" percentWidth="15" property="ruleName" renderer="SailPoint.ruleExpander" sortProperty="ruleName" stateId="ruleName"/>
            <ColumnConfig dataIndex="description" headerKey="impact_column_description" percentWidth="35" property="description" sortProperty="description" stateId="description"/>
            <ColumnConfig dataIndex="IIQ_summary" evaluator="sailpoint.web.view.lcm.WorkItemViolationSummaryColumn" headerKey="impact_column_summary" percentWidth="35" property="IIQ_summary" sortProperty="IIQ_summary" stateId="IIQ_summary"/>
          </List>
        </value>
      </entry>
      <entry key="workItemsArchiveTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="work_item_hdr_id" hideable="true" property="name" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="id" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" flex="1.0" headerKey="name" hideable="true" percentWidth="50" property="description" secondarySort="name" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="type" headerKey="type" hideable="true" property="type" secondarySort="name" sortProperty="type" sortable="true" stateId="type"/>
            <ColumnConfig dataIndex="requester" headerKey="label_requester" hideable="true" property="requester" secondarySort="name" sortProperty="requester" sortable="true" stateId="requester"/>
            <ColumnConfig dataIndex="ownerName" headerKey="owner" hideable="true" property="ownerName" secondarySort="name" sortProperty="ownerName" sortable="true" stateId="ownerName"/>
            <ColumnConfig dataIndex="completer" headerKey="completer" hideable="true" property="completer" secondarySort="name" sortProperty="completer" sortable="true" stateId="completer"/>
            <ColumnConfig dataIndex="signed" headerKey="electronically_signed" hidden="true" hideable="true" property="signed" renderer="SailPoint.grid.Util.renderBoolean" secondarySort="name" sortProperty="signed" sortable="true" stateId="signed"/>
            <ColumnConfig dataIndex="assignee" headerKey="inbox_hdr_assignee" hidden="true" hideable="true" property="assignee" secondarySort="name" sortProperty="assignee" sortable="true" stateId="assignee"/>
            <ColumnConfig dataIndex="created" headerKey="created" hideable="true" property="created" secondarySort="name" sortProperty="created" sortable="true" stateId="created"/>
            <ColumnConfig dataIndex="modified" headerKey="modified" hideable="true" property="modified" secondarySort="name" sortProperty="modified" sortable="true" stateId="modified"/>
            <ColumnConfig dataIndex="archived" headerKey="archived" hideable="true" property="archived" secondarySort="name" sortProperty="archived" sortable="true" stateId="archived"/>
            <ColumnConfig dataIndex="level" headerKey="priority" hideable="true" property="level" secondarySort="name" sortProperty="level" sortable="true" stateId="level"/>
            <ColumnConfig dataIndex="identityRequestId" headerKey="work_item_hdr_access_request_id" hideable="true" property="identityRequestId" renderer="SailPoint.Dashboard.Grid.WorkItem.renderID" secondarySort="name" sortProperty="identityRequestId" sortable="true" stateId="identityRequestId" width="150"/>
          </List>
        </value>
      </entry>
      <entry key="workgroupMemberColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="firstname" headerKey="firstName" hideable="true" property="firstname" sortProperty="firstname" sortable="true" stateId="firstname"/>
            <ColumnConfig dataIndex="lastname" headerKey="lastName" hideable="true" property="lastname" sortProperty="lastname" sortable="true" stateId="lastname"/>
          </List>
        </value>
      </entry>
      <entry key="workgroupTableColumns">
        <value>
          <List>
            <ColumnConfig dataIndex="name" headerKey="name" hideable="true" property="name" sortProperty="name" sortable="true" stateId="name"/>
            <ColumnConfig dataIndex="description" headerKey="description" hideable="true" property="description" sortProperty="description" sortable="true" stateId="description"/>
            <ColumnConfig dataIndex="modified" dateStyle="short" headerKey="modified" hideable="true" property="modified" sortProperty="modified" sortable="true" stateId="modified"/>
          </List>
        </value>
      </entry>
    </Map>
  </Attributes>
</UIConfig>


