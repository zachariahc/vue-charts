<template>
<mdb-container class="mt-5">
  <mdb-row class="mt-5 align-items-center justify-content-start">
    <h4 class="demo-title"><strong>Tables</strong></h4>
    <a href="https://mdbootstrap.com/docs/vue/tables/additional/?utm_source=DemoApp&utm_medium=MDBVueFree" waves-fixed class="border grey-text px-2 border-light rounded ml-2" target="_blank"><mdb-icon icon="graduation-cap" class="mr-2"/>Docs</a>
  </mdb-row>
  <hr />

	<section class="demo-section">
		<h4>Basic example</h4>
		<section>
			<mdb-tbl>
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Table head options</h4>
		<section>
			<mdb-tbl>
				<mdb-tbl-head color="primary-color" textWhite>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Striped rows</h4>
		<section>
			<mdb-tbl striped>
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Bordered table</h4>
		<section>
			<mdb-tbl bordered>
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Borderless table</h4>
		<section>
			<mdb-tbl borderless>
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Hoverable rows</h4>
		<section>
			<mdb-tbl hover>
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Small table</h4>
		<section>
			<mdb-tbl sm>
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Captions</h4>
		<section>
			<mdb-tbl>
				<caption>Example caption</caption>
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Table fixed header</h4>
		<section>
			<mdb-tbl class="fixed-header">
				<mdb-tbl-head>
					<tr>
						<th>#</th>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>1</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>2</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
					<tr scope="row">
						<td>3</td>
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

	<section class="demo-section">
		<h4>Table fixed column</h4>
		<section>
			<mdb-tbl class="fixed-column">
				<mdb-tbl-head>
					<tr>
						<th>thead col 1</th>
						<th>thead col 2</th>
						<th>thead col 3</th>
						<th>thead col 4</th>
						<th>thead col 5</th>
						<th>thead col 6</th>
						<th>thead col 7</th>
						<th>thead col 8</th>
						<th>thead col 9</th>
						<th>thead col 10</th>
						<th>thead col 11</th>
						<th>thead col 12</th>
						<th>thead col 13</th>
						<th>thead col 14</th>
						<th>thead col 15</th>
						<th>thead col 16</th>
						<th>thead col 17</th>
						<th>thead col 18</th>
					</tr>
				</mdb-tbl-head>
				<mdb-tbl-body>
					<tr scope="row">
						<td>tbody col 1</td>
						<td>tbody col 2</td>
						<td>tbody col 3</td>
						<td>tbody col 4</td>
						<td>tbody col 5</td>
						<td>tbody col 6</td>
						<td>tbody col 7</td>
						<td>tbody col 8</td>
						<td>tbody col 9</td>
						<td>tbody col 10</td>
						<td>tbody col 11</td>
						<td>tbody col 12</td>
						<td>tbody col 13</td>
						<td>tbody col 14</td>
						<td>tbody col 15</td>
						<td>tbody col 16</td>
						<td>tbody col 17</td>
						<td>tbody col 18</td>
					</tr>
				</mdb-tbl-body>
			</mdb-tbl>
		</section>
	</section>

</mdb-container>
</template>

<script>
import { mdbTbl, mdbTblHead, mdbTblBody, mdbIcon, mdbContainer, mdbRow } from 'mdbvue';

export default {
  name: 'TablePage',
  components: {
    mdbTbl,
    mdbTblHead,
    mdbTblBody,
    mdbRow,
    mdbIcon,
    mdbContainer
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.fixed-header .table {
	width: auto;
}

.fixed-header thead {
	display: block;
	position: relative;
}

.fixed-header tbody {
	display: block;
	height: 200px;
	overflow-y: scroll;
}

.fixed-column {
	overflow-x: scroll;
	margin-left: 100px;
}

.fixed-column th, .fixed-column td {
	white-space: nowrap;
}

.fixed-column tr th:first-child, .fixed-column tr td:first-child {
	position: absolute;
	width: 100px;
	top: auto;
	margin-left: -100px;
	margin-top: -1px;
}
</style>
