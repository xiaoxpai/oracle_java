
`table_template.jrxml` 

```xml
<!-- Created with Jaspersoft Studio version 7.0.1.final using JasperReports Library version 7.0.1-573496633c2b4074e32f433154b543003f7d2498  -->
<jasperReport name="talbe_sample" language="java" pageWidth="595" pageHeight="842" columnWidth="555" leftMargin="20" rightMargin="20" topMargin="20" bottomMargin="20" uuid="90b65ab4-0f20-406a-8ee0-f0a49480da85">
	<property name="com.jaspersoft.studio.data.sql.tables" value=""/>
	<property name="com.jaspersoft.studio.data.defaultdataadapter" value="Sample DB"/>
	<style name="Table_TH" mode="Opaque" backcolor="#F0F8FF">
		<box>
			<pen lineWidth="0.5" lineColor="#000000"/>
			<topPen lineWidth="0.5" lineColor="#000000"/>
			<leftPen lineWidth="0.5" lineColor="#000000"/>
			<bottomPen lineWidth="0.5" lineColor="#000000"/>
			<rightPen lineWidth="0.5" lineColor="#000000"/>
		</box>
	</style>
	<style name="Table_CH" mode="Opaque" backcolor="#BFE1FF">
		<box>
			<pen lineWidth="0.5" lineColor="#000000"/>
			<topPen lineWidth="0.5" lineColor="#000000"/>
			<leftPen lineWidth="0.5" lineColor="#000000"/>
			<bottomPen lineWidth="0.5" lineColor="#000000"/>
			<rightPen lineWidth="0.5" lineColor="#000000"/>
		</box>
	</style>
	<style name="Table_TD" mode="Opaque" backcolor="#FFFFFF">
		<box>
			<pen lineWidth="0.5" lineColor="#000000"/>
			<topPen lineWidth="0.5" lineColor="#000000"/>
			<leftPen lineWidth="0.5" lineColor="#000000"/>
			<bottomPen lineWidth="0.5" lineColor="#000000"/>
			<rightPen lineWidth="0.5" lineColor="#000000"/>
		</box>
	</style>
	<dataset name="Dataset1" uuid="ccf9483a-762e-4228-91c5-73b5707a30e4">
		<query language="sql"><![CDATA[]]></query>
	</dataset>
	<query language="SQL"><![CDATA[]]></query>
	<background splitType="Stretch"/>
	<title height="79" splitType="Stretch"/>
	<pageHeader height="35" splitType="Stretch"/>
	<columnHeader height="235" splitType="Stretch">
		<element kind="component" uuid="f206da41-2b1d-459f-a1f3-c53091a2e492" x="239" y="35" width="40" height="150">
			<component kind="table">
				<datasetRun uuid="24f56679-f08e-49a6-96b6-3e1e22ea06ad" subDataset="Dataset1">
					<connectionExpression><![CDATA[$P{REPORT_CONNECTION}]]></connectionExpression>
				</datasetRun>
				<column kind="single" uuid="126cecab-a3ca-4221-b2ac-70b729342460" width="40">
					<tableHeader height="30" rowSpan="1" style="Table_TH"/>
					<tableFooter height="30" rowSpan="1" style="Table_TH"/>
					<columnHeader height="30" rowSpan="1" style="Table_CH"/>
					<columnFooter height="30" rowSpan="1" style="Table_CH"/>
					<detailCell height="30" style="Table_TD"/>
					<property name="com.jaspersoft.studio.components.table.model.column.name" value="Column1"/>
				</column>
				<column kind="single" uuid="d6e09486-618a-4f04-bac4-3490a4d62781" width="40">
					<tableHeader height="30" rowSpan="1" style="Table_TH"/>
					<tableFooter height="30" rowSpan="1" style="Table_TH"/>
					<columnHeader height="30" rowSpan="1" style="Table_CH">
						<property name="com.jaspersoft.studio.layout" value="com.jaspersoft.studio.editor.layout.grid.JSSGridBagLayout"/>
					</columnHeader>
					<columnFooter height="30" rowSpan="1" style="Table_CH"/>
					<detailCell height="30" style="Table_TD"/>
					<property name="com.jaspersoft.studio.components.table.model.column.name" value="Column2"/>
				</column>
				<column kind="single" uuid="f36ec9ba-1947-4cc0-bd08-8ddc17fddda0" width="40">
					<tableHeader height="30" rowSpan="1" style="Table_TH"/>
					<tableFooter height="30" rowSpan="1" style="Table_TH"/>
					<columnHeader height="30" rowSpan="1" style="Table_CH"/>
					<columnFooter height="30" rowSpan="1" style="Table_CH"/>
					<detailCell height="30" style="Table_TD"/>
					<property name="com.jaspersoft.studio.components.table.model.column.name" value="Column3"/>
				</column>
				<column kind="single" uuid="381d26c4-b8d4-46b2-8b6f-8a721216df8a" width="40">
					<tableHeader height="30" rowSpan="1" style="Table_TH"/>
					<tableFooter height="30" rowSpan="1" style="Table_TH"/>
					<columnHeader height="30" rowSpan="1" style="Table_CH"/>
					<columnFooter height="30" rowSpan="1" style="Table_CH"/>
					<detailCell height="30" style="Table_TD"/>
					<property name="com.jaspersoft.studio.components.table.model.column.name" value="Column4"/>
				</column>
				<column kind="single" uuid="5ff8bd63-c0cd-43a1-9774-78826a3f286e" width="40">
					<tableHeader height="30" rowSpan="1" style="Table_TH"/>
					<tableFooter height="30" rowSpan="1" style="Table_TH"/>
					<columnHeader height="30" rowSpan="1" style="Table_CH"/>
					<columnFooter height="30" rowSpan="1" style="Table_CH"/>
					<detailCell height="30" style="Table_TD"/>
					<property name="com.jaspersoft.studio.components.table.model.column.name" value="Column5"/>
				</column>
				<column kind="single" uuid="a5bc3d32-56fd-4aca-8618-168cd956681a" width="40">
					<tableHeader height="30" rowSpan="1" style="Table_TH"/>
					<tableFooter height="30" rowSpan="1" style="Table_TH"/>
					<columnHeader height="30" rowSpan="1" style="Table_CH"/>
					<columnFooter height="30" rowSpan="1" style="Table_CH"/>
					<detailCell height="30" style="Table_TD"/>
					<property name="com.jaspersoft.studio.components.table.model.column.name" value="Column6"/>
				</column>
			</component>
			<property name="com.jaspersoft.studio.layout" value="com.jaspersoft.studio.editor.layout.VerticalRowLayout"/>
			<property name="com.jaspersoft.studio.table.style.table_header" value="Table_TH"/>
			<property name="com.jaspersoft.studio.table.style.column_header" value="Table_CH"/>
			<property name="com.jaspersoft.studio.table.style.detail" value="Table_TD"/>
		</element>
	</columnHeader>
	<detail>
		<band height="125" splitType="Stretch"/>
	</detail>
	<columnFooter height="45" splitType="Stretch"/>
	<pageFooter height="54" splitType="Stretch"/>
	<summary height="42" splitType="Stretch"/>
</jasperReport>

```


`design` 




