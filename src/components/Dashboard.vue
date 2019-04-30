<template>
     <section>
            <div class="user-image-container">
                <img src="https://lh3.googleusercontent.com/Qs83uclB6-Qy2_mgiist2bjJrcp6G6MUKkrHtRPtGIpaRGFvcEc25Z8mpYI1bJXQ_u81BpwIcOIrxW7u-0xmp0jez7us3kNQB0FIYC49PxxAkbY7QTK21024NyJxEJmivpCoWbXAhtx2OFOdPpj6vfHsODuZQydCzxnCh49ZAdKDbB7ShIdlKei65X34F8px4fcVYXEP3umUGQlX8Dgd7Xmk5DMWK5To3z72ipBasBK1KwgNoKfXbg96d0g_a4hgtaJPrj4aereSqeP1ZYwBCWRQ0pBGgZqzYt2QmGycR7ogOxxxT6eEyw5TAktDzqTriUOFh7rwTgcYHu7SQQwoF2wcRjkS4YAyq93PISE36nFLQbYViIthJFrcK10q04oBrDjCo59ianzzZGopy02mTwblbcYCP0CjK24Px0e2cJ3Y1TgFGDJHR33P-44l0j185tBGzJOsnPly1mbB1V3cgtNy4G0LIi2Q064RpuJeSkpaDslA8Fe2U0G580PHhXe0foVIbDfGELpXD3aEjL6pFPyt2B4pqthqhEfZ2Rg3hj3D5or37MDZDP630NXQW8ZWN_5xyzaCV22FKIFbg7D_rh-sJFQC0boc6eAg45n1BQl1NBXJXIlbM8VUKOQcl77SAGiCAUA6U-PFQBhBXLEDfTtrZQFZDaM7PNhVjPtUUELi0ZLjzLA24DvFpi_GsSR1Qp9GbHpVoAyNFMTBtERH6hcZ=w1204-h903-no">
                <caption>{{user}}</caption>
                <p>Cash: ${{userCash}}</p>
            </div>
            <div class="user-dashboard-container">
                <table>
                    <thead>
                        <tr>
                            <th></th>
                            <th>week</th>
                            <th>month</th>
                            <th>year</th>
                        </tr>                      
                    </thead>
                    <tbody>
                        <tr>
                            <th>Roster Value</th>
                            <td>data</td>
                            <td>data</td>
                            <td>data</td>
                        </tr>
                        <tr>
                            <th>Earnings</th>
                            <td>data</td>
                            <td>data</td>
                            <td>data</td>
                        </tr>
                        <tr>
                            <th>Record</th>
                            <td>data</td>
                            <td>data</td>
                            <td>data</td>
                        </tr>
                        <tr>
                            <th>Other Cat</th>
                            <td>data</td>
                            <td>data</td>
                            <td>data</td>
                        </tr>
                    </tbody>
                </table>
            </div>
     </section>
</template>

<script>
export default {
    data() {
        return {
            user: "Chewy",
            userCash: "49.63"
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
    section {
        background: $lighter;
        color: $darker;
        padding: 1em;
        display: flex;
        font-family: $font-logo;
    }
    .user-dashboard-container {
        margin: auto;
    }
    .user-image-container {
        width: 20%;
    }
    .user-image-container img {
        width: 60px;
        border-radius: 50%;
    }
    table {
        font-size: 80%;
        text-align: center;
    }
</style>